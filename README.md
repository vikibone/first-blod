javascript demo-2改变link属性实现皮肤变换<br>要点:<br>oSkin[i].onclick = function ()
		{
			for(var p in oSkin) oSkin[p].className = "";<br>
			this.className = "current";<br>
			oLink['href'] = this.id + ".css";<br>				
		}	
