<script>
    let checked = false
</script>

<div class="scoped-js-component">
    Clicking the button below should only toggle the checkbox in this specific instance of the <code>&ltSvelte&gt</code> component.
    <div class="scoped-js-component__interactive-area">
        <button type="button" class="button" on:click={() => checked = !checked}>Click Here</button>
        <input type="checkbox" value="vanilla" bind:checked={checked} />
    </div>
</div>