<!--header-->
<table>
  <tr><td colspan="2"><a href="https://github.com/ChungGyeon">←There is no place to go back</a></td></tr>
  <tr><th colspan="2"><h3><img src=https://capsule-render.vercel.app/api?type=venom&color=gradient&height=300&section=header&text=Always%20learning&fontSize=90></h3></th></tr>
  <tr><td colspan="2" align="center"><p>i dont have anything, but im decorating it</p>
</td></tr>
  <tr>
    <th rowspan="3">Specification<br><sub><a href="metadata.yml">→ Full specification</a></sub></th>
    <td><a href="/source/plugins/screenshot/README.md" title="📸 Website screenshot">📸</a> <a href="/source/plugins/gists/README.md" title="🎫 Gists">🎫</a> <a href="/source/plugins/isocalendar/README.md" title="📅 Isometric commit calendar">📅</a> <a href="/source/plugins/languages/README.md" title="🈷️ Languages activity">🈷️</a> <a href="/source/plugins/lines/README.md" title="👨‍💻 Lines of code changed">👨‍💻</a> <a href="/source/plugins/pagespeed/README.md" title="⏱️ Google PageSpeed">⏱️</a> <a href="/source/plugins/traffic/README.md" title="🧮 Repositories traffic">🧮</a></td>
  </tr>
  <tr>
    <td><code>👤 LJH</code> <code>👥 Chungbuk National University</code></td>
  </tr>
  <tr>
    <td><code>*️⃣ C</code> <code>*️⃣ C++</code> <code>*️⃣ JPEG</code> <code>#️⃣ JSON</code></td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="https://github.com/lowlighter/metrics/blob/examples/metrics.terminal.svg" alt=""></img>
      <img width="900" height="1" alt="">
    </td>
  </tr>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hacker Typer Style</title>
    <style>
        body {
            background-color: black;
            color: green;
            font-family: 'Courier New', Courier, monospace;
            white-space: pre-wrap;
        }

        #output {
            padding: 20px;
            font-size: 1.2rem;
        }
    </style>
</head>
<body>

<div id="output"></div>

<script>
    // 해커 스타일 타이핑 데이터 (예시로 파이썬 코드)
    const code = `import random

def hacker_simulation():
    print("Simulating hacking...")
    data = [random.randint(0, 100) for _ in range(10)]
    print(f"Hacked data: {data}")

hacker_simulation()`;

    const output = document.getElementById('output');
    let index = 0;

    // 키보드 입력 시 텍스트가 추가되도록 설정
    document.addEventListener('keydown', () => {
        if (index < code.length) {
            output.innerText += code[index];
            index++;
        }
    });
</script>
</table>
<!--/header-->

[![My GitHub stats](https://github-readme-stats.vercel.app/api?username=ChungGyeon)](https://github.com/ChungGyeon/github-readme-stats)
