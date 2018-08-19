# mausume-home
<！DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>position</title>
	<style type="text/css">
		*{
		   padding: 0;
		   margin: 0;
		}
		.page{
			width: 100%;
			height: 4043px;
			background: url("mooc.png") center top no-repeat;
		}
		.nav{
			width: 160px;
			height: 205px;
			position: fixed;
			left:0;
			top: 50%;
			margin-top: -103px;
			font-family: 'Microsoft YaHei';
		}
		.nav-li{
			width: 160px;
			height: auto;
			border-bottom: 1px solid #FFF;
			background: #333;
			text-align: center;
			line-height: 40px;
			color: #FFF;
			font-size: 16px;
			cursor: pointer;

		}
		.nav-li ul{
			width: 160px;
			height: auto;
            background: #FFF;
            display: none;
		}
		.nav-li:hover ul{
            display: block; 
		}
		.nav-li ul li{
			width: 160px;
			height: 40px;
			border-bottom: 1px dashed #666;
			color: #333;
			text-align: center;
			line-height: 40px;
			position: relative;
		}
		.tit{
			width: 160px;
			height: 40px;
		}
		.list-3{
			width: 160px;
			height: auto;
			position: absolute;
			left: 150px;
			top: 0;
			display: none;
		}
		.list-3DOM{
			width: 160px;
			height: 40px;
			background: #444;
			border: 1px solid #FFF;
			text-align: center;
			line-height: 40px;
			color: #FFF;

		}
		.nav-li ul li:hover .list-3{
			display: block;
		}
	</style>
</head>
<body>
	<div class="page"> 
         <div class="nav">
         	<div class="nav-li">
         	<div class="tit">固定的标题栏</div>
         	<ul>
         		<li> 
                  二级栏目  
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目 
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目 
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div> 
         		</li>
         	</ul>

         </div>
<div class="nav-li">
         	<div class="tit">固定的标题栏</div>
         	<ul>
         		<li> 
                  二级栏目  
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目 
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目 
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div> 
         		</li>
         	</ul>

         </div>
 <div class="nav-li">
         	<div class="tit">固定的标题栏</div>
         	<ul>
         		<li> 
                  二级栏目  
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目 
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目 
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div> 
         		</li>
         	</ul>

         </div>
         <div class="nav-li">
         	<div class="tit">固定的标题栏</div>
         	<ul>
         		<li> 
                  二级栏目  
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目 
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目 
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div>
         		</li>
         		<li> 
                  二级栏目
                  <div class="list-3">
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
                  <div class="list-3DOM">三级栏目</div>
              </div> 
         		</li>
         	</ul>

         </div>        
         </div>
	</div>
</body>	
</html>
