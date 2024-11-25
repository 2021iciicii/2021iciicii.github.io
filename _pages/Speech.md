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
            <ul>
                <li><a href="talk1/">Prof. Leonid Alekseevich Ivanov: Promising Areas of Research and Technological Cooperation in Different Fields of Engineering</a></li>
                <li><a href="talk2/">Prof. Qingfu Zhang: Decomposition Based Multiobjective Evolutionary Computation</a></li>
                <li><a href="talk3/">Prof. Kaushik Rajashekara: Power Electronics and Communications with Intelligent Control Enabled Smart Grid</a></li>
                <li><a href="talk4/">Prof. Zengguang Hou: Enhancement of Engagement Based on BCI for Rehabilitation Robotics</a></li>
                <li><a href="talk5/">Prof. Xinye Cai: Some Advances in Optimization Based on Computational Intelligence and Their Applications in Aviation</a></li>
                <li><a href="talk6/">Prof. Hui Li: Variable-Length Optimization via Evolutionary Computation</a></li>
                <li><a href="talk7/">Prof. Zhou Zhao: Intelligent Interaction-Oriented Multimodal Semantic Understanding</a></li>
                <li><a href="talk8/">Prof. Shane Xie: Reconfigurable Exoskeleton with Enhanced Autonomy and Intelligence for Effective Home-Based Rehabilitation</a></li>
                <li><a href="talk9/">Prof. Arturo Suman Bretas: Cyber-Physical Secure Energy Transition: Models and Algorithms for a Resilient Power System Operation</a></li>
                <li><a href="talk10/">Prof. Haibin Zhu: E-CARGO and Role-Based Collaboration</a></li>
            </ul>
        </div>
        <div class="speech-column">
            <ul>
                <li><a href="talk1/">Prof. Leonid Alekseevich Ivanov: Promising Areas of Research and Technological Cooperation in Different Fields of Engineering</a></li>
                <li><a href="talk2/">Prof. Qingfu Zhang: Decomposition Based Multiobjective Evolutionary Computation</a></li>
                <li><a href="talk3/">Prof. Kaushik Rajashekara: Power Electronics and Communications with Intelligent Control Enabled Smart Grid</a></li>
                <li><a href="talk4/">Prof. Zengguang Hou: Enhancement of Engagement Based on BCI for Rehabilitation Robotics</a></li>
                <li><a href="talk5/">Prof. Xinye Cai: Some Advances in Optimization Based on Computational Intelligence and Their Applications in Aviation</a></li>
                <li><a href="talk6/">Prof. Hui Li: Variable-Length Optimization via Evolutionary Computation</a></li>
                <li><a href="talk7/">Prof. Zhou Zhao: Intelligent Interaction-Oriented Multimodal Semantic Understanding</a></li>
                <li><a href="talk8/">Prof. Shane Xie: Reconfigurable Exoskeleton with Enhanced Autonomy and Intelligence for Effective Home-Based Rehabilitation</a></li>
                <li><a href="talk9/">Prof. Arturo Suman Bretas: Cyber-Physical Secure Energy Transition: Models and Algorithms for a Resilient Power System Operation</a></li>
                <li><a href="talk10/">Prof. Haibin Zhu: E-CARGO and Role-Based Collaboration</a></li>
            </ul>
        </div>
        <div class="speech-column">
            <ul>
                <li><a href="talk1/">Prof. Leonid Alekseevich Ivanov: Promising Areas of Research and Technological Cooperation in Different Fields of Engineering</a></li>
                <li><a href="talk2/">Prof. Qingfu Zhang: Decomposition Based Multiobjective Evolutionary Computation</a></li>
                <li><a href="talk3/">Prof. Kaushik Rajashekara: Power Electronics and Communications with Intelligent Control Enabled Smart Grid</a></li>
                <li><a href="talk4/">Prof. Zengguang Hou: Enhancement of Engagement Based on BCI for Rehabilitation Robotics</a></li>
                <li><a href="talk5/">Prof. Xinye Cai: Some Advances in Optimization Based on Computational Intelligence and Their Applications in Aviation</a></li>
                <li><a href="talk6/">Prof. Hui Li: Variable-Length Optimization via Evolutionary Computation</a></li>
                <li><a href="talk7/">Prof. Zhou Zhao: Intelligent Interaction-Oriented Multimodal Semantic Understanding</a></li>
                <li><a href="talk8/">Prof. Shane Xie: Reconfigurable Exoskeleton with Enhanced Autonomy and Intelligence for Effective Home-Based Rehabilitation</a></li>
                <li><a href="talk9/">Prof. Arturo Suman Bretas: Cyber-Physical Secure Energy Transition: Models and Algorithms for a Resilient Power System Operation</a></li>
                <li><a href="talk10/">Prof. Haibin Zhu: E-CARGO and Role-Based Collaboration</a></li>
            </ul>
        </div>
    </div>
</div>


<style>

.speech-container {
    position: fixed; /* 固定在页面的某个位置 */
    top: 0; /* 可以根据需要调整位置 */
    left: 0; /* 可以根据需要调整位置 */
    width: 100vw; /* 占满视口的宽度 */
    padding: 30px;
    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    z-index: 1000; /* 使其浮动在其他内容之上 */
}



.speech-container h1 {
    font-size: 2.5em; /* 增大标题大小 */
    color: #2c3e50; /* 标题颜色 */
    margin-bottom: 20px; /* 标题与内容之间的间距 */
    text-align: center; /* 标题居中 */
}

.speech-container ul {
    list-style-type: none; /* 去掉默认的列表样式 */
    padding: 0; /* 去掉内边距 */
}

.speech-container li {
    margin: 15px 0; /* 每个列表项之间的间距 */
    padding: 15px; /* 列表项内边距 */
    background-color: #f1f1f1; /* 列表项背景色 */
    border: 1px solid #ddd; /* 边框 */
    border-radius: 5px; /* 圆角边框 */
    transition: transform 0.3s, box-shadow 0.3s; /* 过渡效果 */
}

.speech-container li:hover {
    transform: translateY(-5px); /* 悬停效果：向上移动 */
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2); /* 鼠标悬停阴影效果 */
}

.speech-container li a {
    text-decoration: none; /* 去掉链接下划线 */
    color: #2980b9; /* 链接颜色 */
    font-weight: bold; /* 链接字体加粗 */
}

.speech-container li a:hover {
    text-decoration: underline; /* 悬停时添加下划线 */
}

.speeches {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.speech-column {
    flex: 1;
    min-width: 30%;
    padding: 10px;
}

.speech-column ul {
    list-style-type: none;
    padding: 0;
}

.speech-column li {
    margin-bottom: 10px;
}

.speech-column a {
    text-decoration: none;
    color: #007bff;
    font-weight: bold;
}

.speech-column a:hover {
    text-decoration: underline;
}

</style>
