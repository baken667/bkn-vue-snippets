# Bkn Code Snippets

This extension adds new snippets for `.vue` files, helping you quickly scaffold Vue components using the Composition API and other common patterns.

## Snippets list

- **`vujs`**: JavaScript Composition API component
    ```vue
    <script setup>
    </script>
    <template>

    </template>
    ```
- **`vuts`**: TypeScript Composition API component
    ```vue
    <script lang="ts" setup>
    </script>
    <template>

    </template>
    ```
- **`vu`**: Component without `<script>` tags (template-only component)
    ```vue
    <template>

    </template>
    ```
- **`vuo`**: JavaScript Options API component
    ```vue
    <script>
    export default {
        name: "ExampleComponent",
        data() {
            return {};
        },
    }
    </script>
    <template>

    </template>
    ```

## Installation

- Install the extension via the VSCode marketplace by searching for `Bkn Code Snippets`.
- Alternatively, you can install it directly from the command line:
    ```bash
    code --install-extension baken667.bkn-vue-snippets
    ```

## How to use?

1. Create a new `.vue` file or open an existing one.
2. Type the snippet prefix (e.g., `vujs`, `vuts`, and more), than press `Tab` to expand the snippet.
3. Fill in the necassery fields and customize as needed.

## Contributing

Feel free to open issues or pull requests if you have ideas for new snippets or improvements!

## License

This extension is licensed under the **MIT** License.
