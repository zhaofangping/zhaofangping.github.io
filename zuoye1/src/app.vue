<template>
	<div id="app">
		<div class="container">
			<div class="head">
				<div class="title">起飞页自助建站平台</div>
				<div>
					<div class="scroll">
						<div class="scroll-bar" :class="index==0?'active':''" style="color:#333;font-size:36px;overflow:hidden;height:100px;line-height:100px;white-space: nowrap;text-overflow: ellipsis;">
							<li style="text-align: center; display: block; font-style: normal;">
								<span style="color:#FFFFFF;">与创业为伴,点亮创新,</span>
								<span style="color:#e84c3d;">是云建站的使命.</span>
							</li>
						</div>
						<div class="scroll-bar" :class="index==1?'active':''" style="color:#333;font-size:36px;overflow:hidden;height:100px;line-height:100px;white-space: nowrap;text-overflow: ellipsis;">
							<li style="text-align: center; display: block; font-style: normal;">
								<span style="color:#FFFFFF;">云建站自助平台,</span>
								<span style="color:#e84c3d;">成就梦想</span>
							</li>
						</div>
					</div>
				</div>
				<div class="head-info">
					<div  style="position: relative;;;line-height:1.5em;;background-repeat: no-repeat;;margin-top:0;margin-bottom:0;padding-top:0;padding-bottom:0;padding-right:0;padding-left:0;border-radius:0px;">
						<div class="qfe_wrapper">
							<div style="text-align: center;"><span style="font-size:26px;"><span style="font-family: 微软雅黑体;"><span style="letter-spacing: 3px;"><span style="color: rgb(255, 255, 255);"><span style="font-family: 华文细黑;">自助建站平台</span></span>
								</span>
								</span>
								</span>
						</div>
						</div>
					</div>
					<div class="info-icon">
						<div class="icon">
							<img style="" class="" src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvYjgxZjYwZjI5NWFlMzgzODExMzliNDU2ZTkwMGUyYTEtNDd4NDcucG5n.png" alt="fb" description="" data-attach-id="11458" data-title="fb" title="" src-img="">
						</div>
						<div class="icon">
							<img style="" class="" src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvODUyMjA2ZWViZDZiMmY0YjU1ZjkwZGI3MjNhODRjNWMtNDd4NDcucG5n.png" alt="li" description="" data-attach-id="11460" data-title="li" title="" src-img="">
						</div>
						<div class="icon">
							<img style="" class="" src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvZjU4N2RiMTkzOWE0YjI4NTk0NzA3MjFjYTJhZTYwMDAtNDd4NDcucG5n.png" alt="sk" description="" data-attach-id="11461" data-title="sk" title="" src-img="">
						</div>
						<div class="icon">
							<img style="" class="" src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvOWIxMTg4ODYwZDI4MzE0MTlmNjkyZjJhM2Y5ZTY5OGUtNDd4NDcucG5n.png" alt="tw" description="" data-attach-id="11462" data-title="tw" title="" src-img="">
						</div>
						<div class="icon">
							<img style="" class="" src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvZDczNTgwOTlmZWEzN2UyY2E4YTVjZWVjNmIxMDU4NmUtNDd4NDcucG5n.png" alt="ye" description="" data-attach-id="11463" data-title="ye" title="" src-img="">
						</div>
						<div class="icon">
							<img style="" class="" src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDcvZjcxMDlkMGU1YmUwZWQ1MjA5ZTk0YjFlYjMwMzY3YjYtNDd4NDcucG5n.png" alt="yt" description="" data-attach-id="11464" data-title="yt" title="" src-img="">
						</div>
					</div>
					
				</div>

			</div>
			<div class="cont1">
				<div>
					<div style="text-align: center;">
						<span style="color: rgb(51, 51, 51); font-family: 微软雅黑, Verdana, Arial, Helvetica, sans-serif; font-size: 14px; text-align: center; display: block;"><span style="line-height:1;"><span style="font-family: 微软雅黑;"><span style="word-wrap: break-word; word-break: break-all; color: rgb(232, 76, 61);"><span style="word-wrap: break-word; word-break: break-all; font-size: 30px;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您的创业梦想需要一个非同凡响的网站</font></font></span></span>
						</span>
						</span>
						</span>
					</div>
					<div style="position: relative;line-height:1.5em;;background-repeat: no-repeat;;margin-top:25px;">
						<div>
							<div>
								<div style="text-align: center;"><span style="font-family:微软雅黑;"><span style="word-wrap: break-word; word-break: break-all; color: rgb(105, 105, 105);"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">云建站倾力打造的一个从网站建设.网网站运营管理到网站推广的自动化免费建站平台</font></font></span></span>
								</div>
							</div>

						</div>
					</div>
				</div>
				<div style="display: flex;text-align: center;padding:30px 40px;">
					<div style="flex:1;margin-right:40px;">
						<div>
							<img width="106" height="101" src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvZjgxMjkwZTg3YTEzM2ZkNWFiM2IzY2ExNjdhNTA3ZDgucG5n.png" class="front_image  attachment-full" alt="pic1" title="" description="" data-title="pic1" src-img="" style="">
						</div>
						<div style="position: relative;;;line-height:1.5em;;background-color: transparent;background-repeat: no-repeat;;margin-top:10px;">
							<div class="qfe_wrapper">
								<div style="text-align: center;"><span style="font-size:18px;"><span style="color:#696969;"><span style="font-family: 微软雅黑; background-color: transparent; line-height: 1.5em; word-spacing: normal;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简单易用,随需而变</font></font></span></span>
									</span>
								</div>
							</div>
						</div>
						<div  style="position: relative;;;line-height:1.5em;;background-repeat: no-repeat;;margin-top:15px;margin-bottom:0;padding-top:0;padding-bottom:0;padding-right:0;padding-left:0;border-radius:0px;">
		<div class="qfe_wrapper">
			<div style="text-align: center;"><span style="font-size:16px;"><span style="font-family:微软雅黑;"><span style="color:#808080;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">互联网创业瞬息万变,天下武功,唯快不破.创业者可以按需选择起飞页中精美的网页模板,预置栏目,快速添加和编辑网页</font></font></span></span></span><span style="font-size:16px;"><span style="font-family:微软雅黑;"><span style="color:#808080;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无需编程,一步即创建一个炫酷高颜值的网站.网站从无到</font></font></span></span></span><span style="font-size:16px;"><span style="font-family:微软雅黑;"><span style="color:#808080;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有,倚马可待.</font></font></span></span></span></div>

		</div> 
	</div>
					</div>
					<div style="flex:1;text-align: center;margin-right:40px;">
						<div>
							<img width="106" height="101" src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvZjgxMjkwZTg3YTEzM2ZkNWFiM2IzY2ExNjdhNTA3ZDgucG5n.png" class="front_image  attachment-full" alt="pic1" title="" description="" data-title="pic1" src-img="" style="">
						</div>
						<div style="position: relative;;;line-height:1.5em;;background-color: transparent;background-repeat: no-repeat;;margin-top:10px;">
							<div class="qfe_wrapper">
								<div style="text-align: center;"><span style="font-size:18px;"><span style="color:#696969;"><span style="font-family: 微软雅黑; background-color: transparent; line-height: 1.5em; word-spacing: normal;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持多终端跨屏展示</font></font></span></span>
									</span>
								</div>
							</div>
						</div>
						<div  style="position: relative;;;line-height:1.5em;;background-repeat: no-repeat;;margin-top:15px;">
		<div class="qfe_wrapper">
			<div style="text-align: center;"><span style="font-size:16px;"><span style="font-family:微软雅黑;"><span style="color:#808080;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在移动互联网全面渗透时,创业者需要一个随屏幕大小不同而自动伸缩的网站,这样同一份内容都可为不同终</font></font></span></span></span><span style="font-size:16px;"><span style="font-family:微软雅黑;"><span style="color:#808080;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端用户带来最佳用户体验.微企点使用最新的HTML5响</font></font></span></span></span><span style="font-size:16px;"><span style="font-family:微软雅黑;"><span style="color:#808080;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应式技术,网页界面随不同屏幕尺寸自动伸缩.</font></font></span></span></span></div>

		</div> 
	</div>
					</div>
					<div style="flex:1;text-align: center;margin-right:40px;">
						<div>
							<img width="106" height="101" src="https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvZjgxMjkwZTg3YTEzM2ZkNWFiM2IzY2ExNjdhNTA3ZDgucG5n.png" class="front_image  attachment-full" alt="pic1" title="" description="" data-title="pic1" src-img="" style="">
						</div>
						<div style="position: relative;;;line-height:1.5em;;background-color: transparent;background-repeat: no-repeat;;margin-top:10px;">
							<div class="qfe_wrapper">
								<div style="text-align: center;"><span style="font-size:18px;"><span style="color:#696969;"><span style="font-family: 微软雅黑; background-color: transparent; line-height: 1.5em; word-spacing: normal;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">页面要炫酷,颜值要高</font></font></span></span>
									</span>
								</div>
							</div>
						</div>
						<div style="position: relative;;;line-height:1.5em;;background-repeat: no-repeat;;margin-top:15px;">
							<div class="qfe_wrapper">
								<div style="text-align: center;"><span style="font-size:16px;"><span style="font-family:微软雅黑;"><span style="color:#808080;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人靠衣装马靠鞍,一个炫酷的网站才配得上创业者的新潮创意.微企点采用HTML5最新技术,拥有大气舒适的界面和众多</font></font></span></span>
									</span><span style="font-size:16px;"><span style="font-family:微软雅黑;"><span style="color:#808080;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">精美模板,用起飞页制作一个高逼格.高颜值的炫酷网站, </font></font></span></span>
									</span><span style="font-size:16px;"><span style="font-family:微软雅黑;"><span style="color:#808080;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">让您的创业项目脱颖而出,非同凡响.</font></font></span></span>
									</span>
								</div>

							</div>
						</div>
					</div>
				</div>

			</div>
			<div class="cont2">
			<!--<div class="section-background-overlay background-overlay grid-overlay-0 " style="background-color: rgba(5,5,5,0.3);">
				<div class=" background-overlay grid-overlay-" style="background-color:transparent;width:100%;"></div>
			</div>-->
			<div class="cont3">
				<div class="top" style="background-image: url('https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvMWYyYjI0N2JjYTc5MjhkYzIyOTRiMjc0M2UyZDI1MWQuanBn.jpg'); background-repeat:no-repeat; background-size:cover; background-attachment:fixed; background-position:0 0%;padding:25px 0px;">
					<div class=" background-overlay grid-overlay-" style="background-color:transparent;width:100%;">
						<i style="display: block; font-style: normal; text-align: center;"><span style="font-family:微软雅黑;"><span style="font-size:24px;"><span style="color: rgb(255, 255, 255);">云建站自助平台</span></span></span></i>
						<i style="display: block; font-style: normal; text-align: center;"><span style="font-family:微软雅黑;"><span style="font-size:24px;"> <span style="color: rgb(232, 76, 61);">上手快.颜值高.跨多屏.自传播.全免费.</span></span></span></i>
					</div>
				</div class="bottom"s>
					<div class="section-background-overlay background-overlay grid-overlay-0 " style="background: url('https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvMWYyYjI0N2JjYTc5MjhkYzIyOTRiMjc0M2UyZDI1MWQuanBn.jpg');">
						<div class=" background-overlay grid-overlay-" style="background-color:transparent;width:810px;margin:0 auto;text-align:center;">
						<span style="display:inline-block;line-height:1.8;"><span style="letter-spacing: 2px;">每一个模版都经过设计、制作、测试、改进等多道工序，力求在达到赏心悦目的艺术视觉效果的同时，又容易定制改变。除此以外，多达180个精美的常用设计模式和30余个功能组件让您在自助建站时得心应手，事半功倍。</span></span>
						</div>
					</div>
				 <div>
				 </div>
			</div>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				index:0,
				timer:''
			}
		},
		mounted() {
			
				console.log(document.querySelectorAll('.scroll-bar').length)
				setInterval(()=>{
					this.index++
					if(this.index >= document.querySelectorAll('.scroll-bar').length){
						this.index=0
					}
				},3000)
		},
	}
</script>

<style>
	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}
	
	.head {
		height: 100vh;
		text-align: center;
		background-image: url('https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDMvNzIzNGQ1MjBkZjBiODhiMDIwYTc3ZmYwZjk1MGM3OGEuanBn.jpg');
		background-repeat: no-repeat;
		background-size: cover;
		background-attachment: fixed;
		background-position: 0 0%;
		padding-top: 220px;
	}
	
	.title {
		line-height: 80px;
		font-size: 60px;
		font-weight: normal;
		font-style: normal;
		color: #ffffff;
		margin-bottom: 43px;
	}
	
	.scroll {
		width: 700px;
		height: 100px;
		margin: 0 auto;
		border-radius: 0px;
		border-top: 2px solid #c9c9c9;
		border-bottom: 2px solid #c9c9c9;
		border-left: 0px solid #c9c9c9;
		border-right: 0px solid #c9c9c9;
		position: relative;
		background-color: rgba(0,0,0,0.4);
		overflow: hidden;
		text-align: center;
	}
	
	.scroll-bar {
		width: 100%;
		/*display: none;*/
		transition: .35s;
		position: absolute;
		top:-100%;
		text-align: center;
		margin:0 auto;
	}
	.active{
		top: 0;
	}
	.head-info {
		margin-top: 56px;
	}
	
	.info-icon {
		text-align: center;
		margin-top: 25px;
	}
	
	.icon {
		margin-bottom: 10px;
		padding-right: 10px;
		display: inline-block;
	}
	
	.cont1 {
		margin-top: 83px;
		padding-bottom: 83px;
	}
</style>