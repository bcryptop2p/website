<template>
  <main>
    <div class="py-16 bg-white dark:bg-gray-800 overflow-hidden">
      <div class="px-4 sm:px-6 lg:px-8">
        <div class="text-lg max-w-prose mx-auto">
          <h1>
            <span
              class="
                font-extrabold
                block
                text-3xl text-gray-900
                dark:text-gray-300
                text-center text-center
              "
              >Disclaimer
            </span>
          </h1>
        </div>
        <div
          class="
            mt-6
            prose prose-cyan
            dark:prose-cyan-light
            prose-lg
            text-gray-500
            dark:text-gray-400
            mx-auto
          "
        >
          <p>
            Switcheo Squad is not affiliated, associated, authorized, endorsed
            by, or in any way officially connected with Switcheo Labs Pte. Ltd.,
            or any of its subsidiaries or its affiliates. The official Switcheo
            website can be found at
            <a href="https://www.switcheo.com" target="_blank" rel="noopener"
              >https://www.switcheo.com</a
            >.
          </p>
          <p>
            The names Switcheo, Carbon, Demex and ZilSwap as well as related
            names, marks, emblems and images are registered trademarks of their
            respective owners.
          </p>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import { useMeta } from "vue-meta";

export default {
  setup() {
    useMeta({
      title: "Disclaimer",
    });
  },
};
</script>
