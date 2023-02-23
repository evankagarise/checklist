<script>
    import { addTodo } from '../../store/TodoStore'
</script>

<section>
    <h3>Checklist</h3>
    <button type="button" on:click={addTodo}>
        Add Task
        <svg
			class="ml-3 h-4 w-4 text-gray-five group-hover:text-green-five group-focus-visible:text-green-five"
			width="32"
			height="32"
			viewBox="0 0 32 32"
			fill="none"
			xmlns="http://www.w3.org/2000/svg"
		>
    </button>
</section>