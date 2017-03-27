<h1>SET API</h1>
<h3 id="header-3"><a href="#header-3"></a>getstock</h3>

<div class="language-js highlighter-rouge"><pre class="highlight"><code><span class="c1">// Javascript code with syntax highlighting.</span>
<span class="kd">[data set] = getstock([symbol],[date period]);</span>
   [symbol] : stock symbol เช่น aot,advanc 
   [date period] : จำนวนระยะเวลาย้อนหลัง เช่น -30 คือย้อนหลังจากวันปัจจุบัน 30 วัน
   [data set] : return open,high,low,close,vol 
</code></pre>
</div>
<img src="img01.png" width="200">

<h3 id="header-3"><a href="#header-3"></a>connect2setapi</h3>
<div class="language-js highlighter-rouge"><pre class="highlight"><code><span class="c1">// Javascript code with syntax highlighting.</span>
<span class="kd">[connection] = connect2setapi([servername],[username],[password]);</span>
   [connection] : connection สำหรับเชื่อมต่อในการเชื่อมต่ออีกครั้ง 
   [servername] : IP Address สำหรับใช้งาน
   [username] : username สำหรับเข้าใช้งานระบบ เช่น adam
   [password] : password สำหรับเข้าใช้งานระบบ เช่น smith
</code></pre>
</div>
