<h1>Screenshot of the website</h1>
<img src="https://raw.githubusercontent.com/123isdar/Bitcoin-Pizza-Day/refs/heads/main/download.png">
<h2>and this is url <a href="https://bitcoin-pizza-day.blogspot.com/" id="rainbowLink">bitcoin-pizza-day.blogspot.com/</a></h2>
<script>
  const link = document.getElementById("rainbowLink");
  const colors = ["red", "orange", "yellow", "green", "blue", "indigo", "violet"];
  let colorIndex = 0;
  setInterval(() => {
    link.style.color = colors[colorIndex];
    colorIndex = (colorIndex + 1) % colors.length;
</script>
