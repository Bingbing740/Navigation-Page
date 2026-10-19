[index.html](https://github.com/user-attachments/files/33670968/index.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>一带一路文化专列 · 高铁客运服务英语实训系统</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: "Microsoft YaHei", "PingFang SC", sans-serif;
    background-color: #f0f6ff;
    background-image: linear-gradient(45deg, #dbe9ff 25%, transparent 25%), linear-gradient(-45deg, #dbe9ff 25%, transparent 25%), linear-gradient(45deg, transparent 75%, #dbe9ff 75%), linear-gradient(-45deg, transparent 75%, #dbe9ff 75%);
    background-size: 40px 40px;
    color: #333; min-height: 100vh;
    display: flex; flex-direction: column; align-items: center; padding: 40px 20px;
  }
  .header { text-align: center; margin-bottom: 40px; }
  .header h1 { font-size: 32px; color: #8b2e2e; margin-bottom: 10px; letter-spacing: 2px; }
  .header p { font-size: 16px; color: #666; }
  .grid {
    display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 24px; width: 100%; max-width: 1000px;
  }
  .card {
    background: #fff; border-radius: 12px; padding: 24px;
    box-shadow: 0 4px 16px rgba(0,0,0,0.08);
    text-decoration: none; color: #333;
    transition: all 0.3s; position: relative; overflow: hidden;
    border-top: 6px solid #b83a3a; display: flex; flex-direction: column;
  }
  .card:hover { transform: translateY(-5px); box-shadow: 0 8px 24px rgba(184,58,58,0.15); }
  .card .tag { font-size: 12px; color: #b83a3a; font-weight: 600; margin-bottom: 8px; }
  .card h2 { font-size: 20px; margin-bottom: 8px; color: #333; }
  .card .en { font-size: 14px; color: #888; font-family: monospace; margin-bottom: 16px; }
  .card .desc { font-size: 13px; color: #666; line-height: 1.6; flex: 1; }
  .card .enter-btn {
    margin-top: 20px; background: #fdf0f0; color: #b83a3a;
    padding: 10px; text-align: center; border-radius: 6px;
    font-weight: 600; font-size: 14px; transition: background 0.2s;
  }
  .card:hover .enter-btn { background: #b83a3a; color: #fff; }
  
  @media (max-width: 600px) {
    .header h1 { font-size: 24px; }
    .grid { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>
  <div class="header">
    <h1>🚄 一带一路文化专列</h1>
    <p>中国传统文化主题专列英语实训系统</p>
  </div>
  
  <div class="grid">
    <a href="task1.html" class="card" style="border-top-color: #4a90d9;">
      <div class="tag">任务一 · 衣</div>
      <h2>衣锦专列 · 苏州站</h2>
      <div class="en">Silk Brocade Express</div>
      <div class="desc">宋锦、苏绣非遗文化。将传统丝织工艺融入乘务服务，讲好中国丝路故事。</div>
      <div class="enter-btn">进入实训系统 →</div>
    </a>

    <a href="task2.html" class="card" style="border-top-color: #d4a017;">
      <div class="tag">任务二 · 食</div>
      <h2>舌尖高铁 · 广州站</h2>
      <div class="en">Yum Cha Express</div>
      <div class="desc">早茶习俗、粤式茶楼文化。在“一盅两件”中展现广府人的待客之道。</div>
      <div class="enter-btn">进入实训系统 →</div>
    </a>

    <a href="task3.html" class="card" style="border-top-color: #b83a3a;">
      <div class="tag">任务三 · 住</div>
      <h2>雅居专列 · 泉州站</h2>
      <div class="en">Dwelling Themed Train</div>
      <div class="desc">闽南红砖古厝、多元宗教建筑。在海上丝绸之路起点感受东方人居之美。</div>
      <div class="enter-btn">进入实训系统 →</div>
    </a>

    <a href="task4.html" class="card" style="border-top-color: #2f855a;">
      <div class="tag">任务四 · 行</div>
      <h2>丝路动车 · 西安站</h2>
      <div class="en">Silk Road Express</div>
      <div class="desc">陆上丝路起点、驼铃古道。串联古今交通变迁，感受高铁出海的时代脉搏。</div>
      <div class="enter-btn">进入实训系统 →</div>
    </a>

    <a href="task5.html" class="card" style="border-top-color: #8b5cf6;">
      <div class="tag">任务五 · 游</div>
      <h2>山河专列 · 敦煌站</h2>
      <div class="en">Mural Express</div>
      <div class="desc">莫高窟壁画艺术、丝路文明交汇。在飞天壁画中领略千年文化交融。</div>
      <div class="enter-btn">进入实训系统 →</div>
    </a>

    <a href="task6.html" class="card" style="border-top-color: #0ea5e9;">
      <div class="tag">任务六 · 用</div>
      <h2>百工专列 · 景德镇站</h2>
      <div class="en">Craftsmen Express</div>
      <div class="desc">青花瓷制瓷工艺、千年瓷都。用流利的英语向世界讲述“China”的故事。</div>
      <div class="enter-btn">进入实训系统 →</div>
    </a>

    <a href="task7.html" class="card" style="border-top-color: #f59e0b;">
      <div class="tag">任务七 · 礼</div>
      <h2>礼乐专列 · 曲阜站</h2>
      <div class="en">Ritual and Music Express</div>
      <div class="desc">孔子礼乐文化、儒家思想。在礼仪之邦传递“礼之用，和为贵”的待客智慧。</div>
      <div class="enter-btn">进入实训系统 →</div>
    </a>

    <a href="task8.html" class="card" style="border-top-color: #dc2626;">
      <div class="tag">任务八 · 传</div>
      <h2>薪火专列 · 北京站</h2>
      <div class="en">Torch-Passing Express</div>
      <div class="desc">文明互鉴、当代“一带一路”倡议。在专列终点站完成八站文化的总结与升华。</div>
      <div class="enter-btn">进入实训系统 →</div>
    </a>
  </div>
</body>
</html>
