<template>
	<div class="page5">
		<h1>{{msg}}</h1>
		<h2>page5</h2>
		<ul>
			<li><a href="#" target=""></a></li>
		</ul>
		<div class="btn-group" role="group" aria-label="...">
			<button type="button" class="btn btn-default">left</button>
			<button type="button" class="btn btn-default">middle</button>
			<button type="button" class="btn btn-default">right</button>
		</div>
		<div id="cc">cc</div>
	</div>
</template>

<script type="text/javascript">
	$(function(){
		alert(123);
	});
	export default{
		name: 'page5',
		data(){
			return{
				msg: 'xxxxxwelcome'
			}
		}
	}
</script>