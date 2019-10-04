<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	@font-face {font-family: "iconfont";
	src:
	  url('data:application/x-font-woff2;charset=utf-8;base64,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') format('woff2'),
	 /* chrome, firefox, opera, Safari, Android, iOS 4.2+ */
	  url('https://iconfont.svg?t=1570161954715#iconfont') format('svg'); /* iOS 4.1- */
	}
	
	.iconfont {
	  font-family: "iconfont" !important;
	  font-size: 16px;
	  font-style: normal;
	  -webkit-font-smoothing: antialiased;
	  -moz-osx-font-smoothing: grayscale;
	}
	
	.icon-rectangle:before {
	  content: "\e72f";
	}
	
	.icon-dianzan:before {
	  content: "\e636";
	}
	
	.icon-qianbao:before {
	  content: "\e602";
	}
	
	.icon-iconzhuanqu_huabanfuben:before {
	  content: "\e521";
	}
	
	.icon-renwu-:before {
	  content: "\e6ff";
	}
	.icon-shezhi:before {
	  content: "\e87a";
	}
	

</style>
