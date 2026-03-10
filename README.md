<!-- Slope Game Card & Embed -->
<div class="card" onclick="openGame('https://storage.y8.com/y8-studio/unity/joll/slope/?key=9757549&value=80527')">
    <span class="category">Arcade</span>
    <h3>Slope</h3>
</div>

<!-- Add this inside your script's openGame function if not already there -->
<script>
    function openGame(url) {
        const player = document.getElementById('player');
        player.src = url;
        player.style.display = 'block';
        document.getElementById('game-grid').style.display = 'none';
        document.getElementById('back-btn').style.display = 'block';
    }
</script>
