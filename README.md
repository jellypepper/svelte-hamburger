# Svelte Hamburger

[![NPM](https://img.shields.io/npm/v/svelte-hamburger)](https://www.npmjs.com/package/svelte-hamburger) [![License](https://img.shields.io/npm/l/svelte-hamburger)](https://github.com/seaneking/svelte-hamburger/blob/master/LICENSE.md)

Animated hamburger icon

### Usage

```sh
npm i svelte-hamburger
```

```svelte
<script>
  import Hamburger from 'svelte-hamburger';
</script>

<Hamburger bind:open />
```

See the [API Docs](https://seaneking.github.io/svelte-hamburger/) for a full overview of props and options.

### Properties

| Property | Type      | Default | Description               |
| -------- | --------- | ------- | ------------------------- |
| `open`   | `boolean` | `false` | Whether hamburger is open |
| `width`  | `number`  | `32`    | Width of the icon         |
| `height` | `number`  | `24`    | Height of the icon        |
| `stroke` | `number`  | `2`     | Thickness of the lines    |
