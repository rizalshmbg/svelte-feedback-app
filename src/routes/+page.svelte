<script>
	import '../../src/app.css'
	import FeedbackList from '../components/FeedbackList.svelte'
	import FeedbackStats from '../components/FeedbackStats.svelte'
	import FeedbackForm from '../components/FeedbackForm.svelte'
</script>

<main class="container">
	<FeedbackForm />
	<FeedbackStats />
	<FeedbackList />
</main>
