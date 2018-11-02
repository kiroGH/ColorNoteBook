<div id="vue_det">
	<h1>site: {{message}}</h1>
	<h1>url: {{url}}</h1>
	<h1>{{details()}}</h1>
</div>
<script type="text/javascript">
	export default {
		data: {
			site: "菜鸟教程",
			url: "www.runob.com",
			alexa: "10000"
		},
		method: {
			details: function() {
				return this.site + " - 学的不仅是技术，更是梦想！";
			}
		}
	}
</script>