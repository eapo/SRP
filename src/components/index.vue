<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <ol>
		<li>
		  <code>&lt;head></code>: <code>&lt;script
  src="https://cdn.../srp.min.js" crossorigin="anonymous" integrity="sha256-/...">&lt;/script></code>
		</li><li>
		  <code>&lt;body></code>: <code>&lt;fieldset id="srp">&lt;legend>Shared Resources&lt;/legend></code></li>
    </ol>
  </div>

	<p><span>A </span><em><span>GPT</span></em><span> guided </span><em><span>Secure Plugin</span></em><span> to connect </span><em><span>Resources</span></em><span> and </span><em><span>Needs</span></em><span> using Additional Incentives. </span><code>#CoNetRes</code></p>

  <p class="read-the-docs"></p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
ol {
	text-align: left;
	}
</style>
