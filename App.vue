<script>
	export default {
		onLaunch: function () {
			console.log('App Launch')
		},
		onShow: function () {
			console.log('App Show')
		},
		onHide: function () {
			console.log('App Hide')
		}
	}
</script>

<style>
	/* 默认主题 */
	:root {
	  --Default-background-color: #F2F2F2;
	  --Highlight-background-color: #FFFFFF;
	  --text-color: #24292E;
	  --text-active-color: #C9D1D9;
	  --border-color: #E1E4E8;
	  --hover-color: #FF3C46;
	  --hover-border-color: #F9826C;
	  --btn-text-color: #FF3C46;
	  --btn-backgroud-color: #FFFFFF;
	  --tabbar-background-color: #161B22;
	  --green: #39B54A;
	  --orange: #FF4500;
	}
	/*浅色主题 */
	@media (prefers-color-scheme: light) {
	  :root {
	    --Default-background-color: #F2F2F2;
	    --Highlight-background-color: #FFFFFF;
	    --text-color: #24292E;
	    --text-active-color: #C9D1D9;
	    --border-color: #E1E4E8;
	    --hover-color: #FF3C46;
	    --hover-border-color: #F9826C;
	    --btn-text-color: #FF3C46;
	    --btn-backgroud-color: #FFFFFF;
	    --tabbar-background-color: #161B22;
	    --green: #39B54A;
	    --orange: #FF4500;
	    --blue: #0081FF;
	  }
	}
	/* 深色主题 */
	@media (prefers-color-scheme: dark) {
	  :root {
	    --Default-background-color: #0D1117;
	    --Highlight-background-color: #161B22;
	    --text-color: #8B949E;
	    --text-active-color: #C9D1D9;
	    --border-color: #30363D;
	    --hover-color: #FF3C46;
	    --hover-border-color: #F9826C;
	    --btn-text-color: #FF3C46;
	    --btn-backgroud-color: #FFFFFF;
	    --tabbar-background-color: #161B22;
	    --green: #39B54A;
	    --orange: #FF4500;
	    --blue: #0081FF;
	  }
	}
	body {
	  color: var(--text-color);
	  background-color: var(--Default-background-color) !important;
	  min-height: 100vh;
	  display: flex;
	  flex-direction: column;
	  align-items: center;
	  justify-content: center;
	  font-size: calc(10px + 2vmin);
	  transition: background-color 0.3s;
	}
</style>
