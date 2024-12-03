---
permalink: /Speech/
redirect_from:
  - /resume
---

{% include base_path %}
<div class="speech-container">
    <h1>Keynote / Invited Speech</h1>
    <div class="speeches">  
        <div class="speech-column">
            <h2>2021</h2>
            <ul>
                <li><a href="talk2-1/">Prof. Leonid Alekseevich Ivanov: Promising Areas of Research and Technological Cooperation in Different Fields of Engineering</a></li>
                <li><a href="talk2-2/">Prof. Qingfu Zhang: Decomposition Based Multiobjective Evolutionary Computation</a></li>
                <li><a href="talk2-3/">Prof. Kaushik Rajashekara: Power Electronics and Communications with Intelligent Control Enabled Smart Grid</a></li>
                <li><a href="talk2-4/">Prof. Zengguang Hou: Enhancement of Engagement Based on BCI for Rehabilitation Robotics</a></li>
                <li><a href="talk2-5/">Prof. Xinye Cai: Some Advances in Optimization Based on Computational Intelligence and Their Applications in Aviation</a></li>
                <li><a href="talk2-6/">Prof. Hui Li: Variable-Length Optimization via Evolutionary Computation</a></li>
                <li><a href="talk2-7/">Prof. Zhou Zhao: Intelligent Interaction-Oriented Multimodal Semantic Understanding</a></li>
                <li><a href="talk2-8/">Prof. Shane Xie: Reconfigurable Exoskeleton with Enhanced Autonomy and Intelligence for Effective Home-Based Rehabilitation</a></li>
                <li><a href="talk2-9/">Prof. Arturo Suman Bretas: Cyber-Physical Secure Energy Transition: Models and Algorithms for a Resilient Power System Operation</a></li>
                <li><a href="talk2-10/">Prof. Haibin Zhu: E-CARGO and Role-Based Collaboration</a></li>
                <li><a href="talk2-11/">Prof. Han Huang: Applications of Optimization Based on Computational Intelligence</a></li>
                <li><a href="talk2-12/">Prof. Jianyong Sun: Research on Optimization Algorithm Based on Artificial Intelligence -- Preliminary Progress</a></li>
                <li><a href="talk2-13/">Prof. Xiaomin Zhu: Research on the Aggregation and Emergence of Swarm Intelligence Based on the Evolutionary Mechanism of Organisms</a></li>
                <li><a href="talk2-14/">Prof. Yun Liang: Generic Interactive Pixel-Level Image Editing</a></li>
                <li><a href="talk2-15/">Prof. Lijun Zhang: The Role of Optimisation and Verification in Promoting a Green Society: Vehicles and Industrial Processes as Examples</a></li>
                <li><a href="talk2-16/">Prof. Lijie Li: Synergies between Nanogenerator Based Sensors and Artificial Intelligence</a></li>
                <li><a href="talk2-17/">Prof. Yaochu Jin: Privacy-Preserving Data-Driven Evolutionary Optimization</a></li>
                <li><a href="talk2-18/">Dr. Shuo Deng: Electron Transport through Dynamic Semiconductor Junction</a></li>
            </ul>
        </div>
    </div>
</div>

<style>
  
.speeches {
    display: flex;
    flex-wrap: wrap;
    justify-content: center; /* 使所有列居中对齐 */
    gap: 20px; /* 每列之间的间距 */
}

.speech-column {
    width: 50%; /* 设置每列宽度为 22%，以便能够容纳四列，并留出间隙 */
    box-sizing: border-box; /* 确保 padding 和 border 不影响整体宽度 */
    padding: 10px;
    background-color: #f9f9f9; /* 给每列添加背景色，使它们更明显 */
    text-align: center; /* 每列内文本居中 */
}

.speech-column h2 {
    font-size: 1.2em; /* 调整标题大小 */
    color: #2c3e50; /* 设置标题颜色 */
    margin-bottom: 12px; /* 与列表之间的间距 */
    text-align: center;
}

.speech-column ul {
    list-style-type: none;
    padding: 0;
}

.speech-column li {
    margin: 15px 0;
    padding: 20px;
    background-color: #f1f1f1;
    border: 1px solid #ddd;
    border-radius: 5px;
    height: 200px; /* 设置固定高度，确保每个框的大小一致 */
    display: flex;
    align-items: center; /* 使文字在框内垂直居中 */
    transition: transform 0.3s, box-shadow 0.3s;
}

.speech-column li:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}

.speech-column li a {
    text-decoration: none;
    color: #2980b9;
    font-weight: bold;
    text-align: center; /* 链接文字居中 */
    width: 100%;
}

.speech-column li a:hover {
    text-decoration: underline;
}


.speech-container {
    position: relative; /* 可选：如果不想保持相对定位，删除这行 */
    width: 100vw; /* 删除这一行，使容器不再强制占满整个视口宽度 */
    margin-left: calc(50% - 50vw); /* 删除这一行，取消强制容器宽度从页面边界开始 */
    padding: 30px;
    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

.speech-container h1 {
    font-size: 2em;
    color: #2c3e50;
    margin-bottom: 20px;
    text-align: center;
    position: sticky; /* 保持标题在页面顶部可见 */
    top: 0;
    background-color: #ffffff;
    padding: 20px;
    z-index: 10;
}
  
</style>
