<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8"/>
<title>Slither Snake Preview</title>
<style>
  body {
    background: #0d1117;
    color: #c9d1d9;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    margin: 0;
    padding: 48px;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 32px;
  }
  h1 { font-weight: 600; font-size: 18px; color: #7aa2f7; margin: 0; }
  .card {
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 12px;
    padding: 24px;
    width: min(960px, 100%);
    box-sizing: border-box;
  }
  .label { color: #7d8590; font-size: 13px; margin-bottom: 12px; }
</style>
</head>
<body>
  <h1>🐍 Animated Slither Snake — Preview</h1>

  <div class="card">
    <div class="label">slither-snake.svg (dark background)</div>
    <object type="image/svg+xml" data="slither-snake.svg" style="width:100%;"></object>
  </div>

  <div class="card" style="background:#ffffff;">
    <div class="label" style="color:#57606a;">slither-snake.svg (light background)</div>
    <object type="image/svg+xml" data="slither-snake.svg" style="width:100%;"></object>
  </div>
</body>
</html>
