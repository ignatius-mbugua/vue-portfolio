<template>
  <div>
    <div
      class="flex flex-col bg-white border border-gray-200 shadow-sm rounded-xl p-4 md:p-12"
    >
      <h1 class="text-3xl font-bold pb-4 text-gray-800">Projects</h1>

      <div v-for="project in projects" :key="project.id">
        <ProjectItem>
          <template #heading>{{ project.title }} </template>
          <template #content>
            {{ project.content }}
          </template>
        </ProjectItem>
      </div>
    </div>
  </div>
</template>

<script setup>
import ProjectItem from "./ProjectItem.vue";
import { ref } from "vue";

const projects = ref([
  {
    id: 1,
    title: "Consultancy Website",
    content:
      "Lorem ipsum dolor sit amet consectetur adipisicing elit.Recusandae perspiciatis commodi maxime iure molestiae exercitationem, officia dolores, iusto delectus eius repellendus numquam? Eum maiores, amet voluptas aliquid quaerat nostrum, laboriosam assumenda labore illum ipsam in consectetur possimus ab exercitationem sit impedit, odio fugiat at. Debitis porro repellendus autem amet repudiandae.",
  },
  {
    id: 2,
    title: "Agriculture Website",
    content: "Lorem ipsum dolor sit amet consectetur adipisicing elit.Recusandae perspiciatis commodi maxime iure molestiae exercitationem, officia dolores, iusto delectus eius repellendus numquam? Eum maiores, amet voluptas aliquid quaerat nostrum, laboriosam assumenda labore illum ipsam in consectetur possimus ab exercitationem sit impedit, odio fugiat at. Debitis porro repellendus autem amet repudiandae.",
  },
  {
    id: 3,
    title: "School Website",
    content: "Lorem ipsum dolor sit amet consectetur adipisicing elit.Recusandae perspiciatis commodi maxime iure molestiae exercitationem, officia dolores, iusto delectus eius repellendus numquam? Eum maiores, amet voluptas aliquid quaerat nostrum, laboriosam assumenda labore illum ipsam in consectetur possimus ab exercitationem sit impedit, odio fugiat at. Debitis porro repellendus autem amet repudiandae.",
  },
]);
</script>
