<template>
	<view class="content">
        <uni-badge text="3" type="success"></uni-badge>
		购物车
	</view>
</template>

<script lang="ts">
	import {
		Component,
		Vue,
		Watch
	} from "vue-property-decorator"
	import uniBadge from "@/components/uni-ui/lib/uni-badge/uni-badge.vue";

	@Component({
		components:{
			uniBadge
		}
	})
	export default class Index extends Vue {
		
	}
</script>
