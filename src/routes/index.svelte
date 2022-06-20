<script>
	import { Dialog } from '@capacitor/dialog';
	import { Toast } from '@capacitor/toast';

	async function show() {
		// await Dialog.alert({
		// 	title: 'Stop',
		// 	message: 'this is an error'
		// });
		await Toast.show({
			text: 'Hello!'
		});
	}
</script>

<button on:click={show}>Show</button>
