# stuning
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>chanllage90</title>
	<style type="text/css">
		p {position: absolute;
		   width: 20px;
		   height: 20px;
		   }
	</style>
</head>
<body>

    <script type="text/javascript">
    	var arr="PESPESPESPESPNNNNPWSPWSPWSPWSP";
    	var x=0;
    	    y=0;
    	    
    	     for(var i=0;i<30;i++){
    	     	var node=document.createElement("P");
    	     	document.getElementsByTagName("body")[0].appendChild(node);
    	    	var pp=document.getElementsByTagName('P')[i];
    	    	if(arr[i]=="P"){
    	    		pp.innerHTML="*";
    	    		pp.style.left=x+"px";
    	    		pp.style.top=y+"px";
    	    		
    	    	}else if(arr[i]=="E"){
                   pp.style.left=x+"px";
                   x=x+20; 
    	    	}else if (arr[i]=="W") {
                   pp.style.left=x+"px";
                   x=x-20;
    	    	}else if (arr[i]=="S") {
    	    	   pp.style.top=y+"px";
    	    	   y=y+20;	
    	    	}else if(arr[i]=="N"){
                   pp.style.top=y+"px";
                   y=y-20;
    	    	}
    	    }
    </script>
</body>
</html>
