<script lang="typescript">
// @ts-ignore
    import module from './crate/Cargo.toml'

    const a: string = 'Svelte',
        b: string = 'Typescript',
        c: string = 'Parcel',
// @ts-ignore
        d: string = module.run()
</script>

<h1>{a} + {b} + {c} + {d}</h1>

<style type="scss">
    h1 {
        font: normal 24pt Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;
        color: dimgray;
        cursor: default;
    }
</style>
