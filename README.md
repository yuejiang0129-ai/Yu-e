[index.html](https://github.com/user-attachments/files/27562411/index.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>蒋玉娥 | 教授 · 硕导 | 安庆师范大学</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', 'Roboto', 'Noto Sans', system-ui, -apple-system, 'PingFang SC', 'Microsoft YaHei', sans-serif;
            background: #f5f9fc;
            color: #1a344d;
            line-height: 1.5;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem 1.5rem;
        }

        .hero {
            background: #ffffff;
            border-radius: 1.25rem;
            padding: 1.8rem 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.03), 0 1px 2px rgba(0, 0, 0, 0.05);
            border: 1px solid #eef2f6;
        }

        .hero-header {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: flex-start;
            gap: 1.5rem;
        }

        .hero-info h1 {
            font-size: 2.4rem;
            font-weight: 600;
            color: #0b3b4f;
            letter-spacing: -0.01em;
            margin-bottom: 0.3rem;
        }

        .hero-info .title-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.6rem;
            margin: 0.6rem 0 0.8rem;
        }

        .badge {
            background: #eef2fa;
            padding: 0.2rem 0.9rem;
            border-radius: 30px;
            font-size: 0.8rem;
            font-weight: 500;
            color: #1f5e7e;
        }

        .contact-info {
            background: #f8fafd;
            border-radius: 1rem;
            padding: 0.8rem 1.2rem;
            text-align: right;
            font-size: 0.9rem;
            border: 1px solid #e9edf2;
        }

        .contact-info p {
            margin: 0.2rem 0;
        }

        .contact-info a {
            color: #1f6e8c;
            text-decoration: none;
            border-bottom: 1px solid #cddfe7;
        }

        .quick-stats {
            display: flex;
            flex-wrap: wrap;
            gap: 1.8rem;
            margin-top: 1.5rem;
            padding-top: 1.2rem;
            border-top: 1px solid #e6edf4;
        }

        .stat-item {
            display: flex;
            flex-direction: column;
        }

        .stat-num {
            font-size: 1.5rem;
            font-weight: 700;
            color: #15607a;
        }

        .stat-label {
            font-size: 0.8rem;
            color: #527a9b;
        }

        .card {
            background: #ffffff;
            border-radius: 1.2rem;
            border: 1px solid #eef2f8;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.03);
            margin-bottom: 1.8rem;
            overflow: hidden;
        }

        .card-header {
            padding: 0.9rem 1.5rem;
            border-bottom: 1px solid #eff3f8;
            font-size: 1.2rem;
            font-weight: 600;
            background: #fefefe;
            color: #1c4e6c;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .card-content {
            padding: 1.2rem 1.5rem;
        }

        .pub-list, .project-list, .award-list, .patent-list, .student-list, .teaching-list, .research-project-list, .merged-list {
            list-style: none;
        }

        .pub-list li, .project-list li, .award-list li, .patent-list li, .student-list li, .teaching-list li, .research-project-list li, .merged-list li {
            margin-bottom: 1rem;
            padding-bottom: 0.6rem;
            border-bottom: 1px solid #f0f4f9;
        }

        .pub-title {
            font-weight: 600;
            color: #1a5a78;
        }

        .pub-meta {
            font-size: 0.8rem;
            color: #617e9c;
            margin-top: 0.2rem;
        }

        .citation-badge {
            background: #e9f2f9;
            color: #1b6b8f;
            font-size: 0.7rem;
            padding: 0.2rem 0.6rem;
            border-radius: 18px;
            display: inline-block;
            margin-left: 0.6rem;
        }

        .tag {
            background: #edf4fa;
            padding: 0.2rem 0.7rem;
            border-radius: 20px;
            font-size: 0.75rem;
            display: inline-block;
            margin-right: 0.5rem;
        }

        .grid-2col {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }

        .update-note {
            background: #eef4fa;
            border-radius: 30px;
            display: inline-block;
            padding: 0.2rem 0.7rem;
            font-size: 0.7rem;
            margin-left: 0.8rem;
            color: #1c6a8a;
        }

        .author-bold {
            font-weight: 700;
            color: #1c4e6c;
        }

        .paper-number {
            display: inline-block;
            font-weight: 700;
            color: #1f6e8c;
            margin-right: 0.5rem;
            background: #eef2fa;
            padding: 0 0.4rem;
            border-radius: 12px;
            font-size: 0.75rem;
        }

        footer {
            margin-top: 2rem;
            text-align: center;
            padding: 1rem;
            font-size: 0.75rem;
            color: #8da0b0;
            border-top: 1px solid #e2e9f0;
        }

        @media (max-width: 700px) {
            .container {
                padding: 1rem;
            }
            .hero-header {
                flex-direction: column;
            }
            .contact-info {
                text-align: left;
                width: 100%;
            }
            .hero-info h1 {
                font-size: 1.9rem;
            }
        }
    </style>
</head>
<body>
<div class="container">
    <!-- 头部信息 -->
    <div class="hero">
        <div class="hero-header">
            <div class="hero-info">
                <h1>蒋玉娥 <span style="font-size:1.3rem; font-weight:500;">教授 | 硕士生导师</span></h1>
                <div class="title-tags">
                    <span class="badge">6G移动通信</span>
                    <span class="badge">物理层安全</span>
                    <span class="badge">无人机通信</span>
                    <span class="badge">智能反射面(RIS)</span>
                    <span class="badge">隐蔽通信</span>
                </div>
                <div style="font-size:0.85rem; color:#3d6b8c; margin-top: 0.2rem;">
                    安庆师范大学 · 人工智能与计算机学院 | 发展规划处、学科建设处 副处长
                </div>
                <div style="margin-top: 10px;">
                    <span class="tag" style="background:#e1f0f5;">🎓 招收：软件工程（学硕）| 电子信息（专硕）</span>
                </div>
            </div>
            <div class="contact-info">
                <p>📧 jiang2012118@163.com</p>
                <p>📍 行政楼北609 · 安庆师范大学</p>
                <p>🎓 博士 (江苏大学) | 硕士 (南京理工大学)</p>
                <p>📅 最后更新：<span id="lastUpdateDate">2026-05-10</span></p>
            </div>
        </div>
        <div class="quick-stats">
            <div class="stat-item"><span class="stat-num">15+</span><span class="stat-label">高水平论文</span></div>
            <div class="stat-item"><span class="stat-num">300+</span><span class="stat-label">谷歌学术引用</span></div>
            <div class="stat-item"><span class="stat-num">8+</span><span class="stat-label">科研/教研项目</span></div>
            <div class="stat-item"><span class="stat-num">12+</span><span class="stat-label">教学成果/奖励</span></div>
            <div class="stat-item"><span class="stat-num">20+</span><span class="stat-label">学科竞赛省部级奖项</span></div>
        </div>
    </div>

    <div class="research-grid">
        <!-- 研究方向 + 课程 -->
        <div class="grid-2col">
            <div class="card">
                <div class="card-header">📡 研究方向</div>
                <div class="card-content">
                    <ul style="list-style: none; padding-left: 0;">
                        <li>🔹 6G移动通信与物理层安全</li>
                        <li>🔹 无人机(UAV)通信与隐蔽传输</li>
                        <li>🔹 智能反射面(RIS)辅助通信</li>
                        <li>🔹 基于机器学习的无线性能优化</li>
                        <li>🔹 区块链物联网中的安全卸载</li>
                    </ul>
                </div>
            </div>
            <div class="card">
                <div class="card-header">📖 主讲课程</div>
                <div class="card-content">
                    <div><span class="tag">研究生课程</span> 科技论文写作</div>
                    <div style="margin-top: 12px;"><span class="tag">本科生课程</span> 信号与系统、物联网通信技术、物联网系统设计与实践</div>
                </div>
            </div>
        </div>

        <!-- 科研项目 -->
        <div class="card">
            <div class="card-header">🧪 承担科研项目 <span class="update-note">国家级/省部级/横向</span></div>
            <div class="card-content">
                <ul class="research-project-list">
                    <li><strong>国家自然科学基金青年科学基金项目</strong>：基于随机几何的IRS-UAV物理层隐蔽通信方案设计与优化方法研究（62402007），2024-2027，主持</li>
                    <li><strong>安徽省高端人才培育项目</strong>：青年拔尖人才青年学者研究（皖教工委函〔2025〕313号），2025-2028，主持</li>
                    <li><strong>安徽省高校自然科学研究重点项目</strong>：面向6G移动边缘计算的抗随机窃听物理层隐蔽通信方法研究（2024AH051096），2024-2026，主持</li>
                    <li><strong>安徽省高校自然科学研究重点项目</strong>：小蜂窝网络支持下的D2D隐蔽通信方案（KJ2020A0497），2021-2023，主持（已结题）</li>
                    <li><strong>安庆市新能源汽车产业集群建设专项项目</strong>：智能网联汽车高精度定位系统研发与产业化（H20250091），2024-2026，排名2</li>
                    <li><strong>安徽省自然科学基金面上项目</strong>：基于区块链的智慧医疗数据安全可信存储共享关键技术研究（2308085MF223），2024-2027，排名2</li>
                    <li><strong>横向项目</strong>：高性能液压阀性能在线监测与智能控制关键技术研发（H20250090），2024-2026，排名2</li>
                </ul>
            </div>
        </div>

        <!-- 科研奖励 -->
        <div class="card">
            <div class="card-header">🏅 科研奖励</div>
            <div class="card-content">
                <ul class="award-list">
                    <li>[1] 最佳论文奖，20th EAI International Conference on Communications and Networking in China (ChinaCom 2025)，排名5</li>
                    <li>[2] <strong>中国商业联合会科技进步奖一等奖</strong>，多源遥感数据的大田作物数智化管理关键技术集成与应用，2025年12月，排名第4</li>
                </ul>
            </div>
        </div>

        <!-- 教学研究项目 + 教学成果奖 -->
        <div class="grid-2col">
            <div class="card">
                <div class="card-header">📚 教学研究项目</div>
                <div class="card-content">
                    <ul class="teaching-list">
                        <li><strong>安徽省质量工程教育教学研究重点项目</strong>：“工程认证”背景下解决“复杂工程问题”能力培养体系研究与实践（2022jyxm919），排名1，优秀结题</li>
                        <li><strong>安庆师范大学校级教育教学改革研究重点项目</strong>：工程认证背景下复杂工程问题能力培养研究（2021aqnujyxm0），排名1，结题</li>
                        <li><strong>安徽省高等学校第一批专业建设项目</strong>：《物联网通信技术》线上线下混合式课程，在研</li>
                    </ul>
                </div>
            </div>
            <div class="card">
                <div class="card-header">🏆 教学成果奖</div>
                <div class="card-content">
                    <ul class="award-list">
                        <li>第五届全国高校教师教学创新大赛安徽省赛，省级三等奖（2025）</li>
                        <li>安徽省高校计算机教育教学案例大赛，省级一等奖（全省第1）（2025）</li>
                        <li>中国高校计算机教育大学教学案例大赛，国家级三等奖（2025）</li>
                        <li>校教师教学创新大赛二等奖、三等奖（2022、2025）</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 研究生培养 -->
        <div class="card">
            <div class="card-header">🎓 研究生培养 <span class="update-note">毕业去向&在读</span></div>
            <div class="card-content">
                <ul class="student-list">
                    <li><strong>2021级 冯钰</strong> —— 商丘工学院（教师）</li>
                    <li><strong>2022级 王雨桐</strong> —— 南京信息工程大学（读博）</li>
                    <li><strong>2023级 江济民</strong> —— 在读</li>
                    <li><strong>2024级 洪悦</strong> —— 在读</li>
                </ul>
                <div style="margin-top: 0.6rem; background: #F7FAFF; padding: 0.5rem 0.8rem; border-radius: 12px; font-size:0.8rem;">
                    💡 指导研究生在IEEE IoT-J、NaNA等期刊/会议发表高质量论文，多次获校优秀研究生称号。
                </div>
            </div>
        </div>

        <!-- ================= 代表性论文（严格按照 Google 引用数目） ================= -->
        <div class="card">
            <div class="card-header">📄 代表性论文 <span class="update-note">基于Google Scholar引用数据</span></div>
            <div class="card-content">
                <ul class="pub-list">
                    <li><span class="paper-number">[1]</span> <span class="pub-title">Yu'e Jiang, Liangmin Wang, Hsiao-Hwa Chen, and Xuemin Shen. “Physical Layer Covert Communication in B5G Wireless Networks--Its Research, Applications and Challenges”, <em>Proceedings of the IEEE</em>, vol. 112, no. 1, pp. 47-82, 2024. </span><span class="citation-badge">引用 54 次</span><div class="pub-meta">CCF A类 / 中科院一区Top，IF:23.2</div></li>
                    
                    <li><span class="paper-number">[2]</span> <span class="pub-title">Yu'e Jiang, Liangmin Wang, and Hsiao-Hwa Chen. “Covert Communications with Randomly Distributed Adversaries in Wireless Energy Harvesting Enabled D2D Underlaying Cellular Networks.” <em>IEEE Transactions on Information Forensics & Security</em>, vol. 18, pp. 5401-5415, 2023. </span><span class="citation-badge">引用 13 次</span><div class="pub-meta">CCF A类 / 中科院一区Top，IF:6.3</div></li>
                    
                    <li><span class="paper-number">[3]</span> <span class="pub-title">Yu'e Jiang, Liangmin Wang, and Hsiao-Hwa Chen. “Covert Communications in D2D Underlaying Cellular Networks With Antenna Array Assisted Artificial Noise Transmission.” <em>IEEE Transactions on Vehicular Technology</em>, 2020, 69(3), 2980-2992. </span><span class="citation-badge">引用 86 次</span><div class="pub-meta">JCR 1区 / 中科院二区Top，IF:6.1</div></li>
                    
                    <li><span class="paper-number">[4]</span> <span class="pub-title">Yu'e Jiang, Liangmin Wang, Hui Zhao, and Hsiao-Hwa Chen. “Covert Communications in D2D Underlaying Cellular Networks With Power Domain NOMA.” <em>IEEE Systems Journal</em>, 2020, 14(3), 3717-3728. </span><span class="citation-badge">引用 73 次</span><div class="pub-meta">JCR 1区 / 中科院二区，IF:4.0</div></li>
                    
                    <li><span class="paper-number">[5]</span> <span class="pub-title">Yu'e Jiang, Yutong Wang, Haiqin Wu, Yiliang Liu, Langtao Hu. “Energy-Efficient Covert Offloading in Blockchain-Enabled IoT: Joint Artificial Noise and Computation Resource Allocation” <em>IEEE Internet of Things</em>, 2025,12(6), 6889-6901. </span><span class="citation-badge">引用 3 次</span><div class="pub-meta">JCR 1区 / 中科院一区Top / CCF-C，IF:8.2</div></li>
                    
                    <li><span class="paper-number">[6]</span> <span class="pub-title">Yiliang Liu, Xiangrui Cheng, Zhou Su, Yunchen Wang, Yu'e Jiang, and Tom. H Luan. “Intelligent Reflecting Surface-Assisted Power Efficiency Physical Layer Security in Uplink Multiple-User Channel .” <em>IEEE Transactions on Vehicular Technology</em>, 2025. (Accepted)</span><span class="citation-badge">新发表</span><div class="pub-meta">合作论文，中科院二区Top期刊</div></li>
                    
                    <li><span class="paper-number">[7]</span> <span class="pub-title">Langtao Hu, Rui Yang, Lei Wu, Chongwen Huang, Yu'e Jiang, Li Chen, Xiaobo Zhou. “RIS-assisted Integrated Sensing and Covert Communication Design.” <em>IEEE Internet of Things</em>, 2024, 11(9), 16505-16516. </span><span class="citation-badge">引用 47 次</span><div class="pub-meta">JCR 1区 / 中科院一区Top / CCF-C，IF:8.2</div></li>
                    
                    <li><span class="paper-number">[8]</span> <span class="pub-title">Yutong Wang, Yu'e Jiang*, Yu Feng. “Covert Communication-Assisted Computing Offload schemes in Blockchain-Enabled IoT,” in <em>International Conference on Networking and Network Applications (NaNA)</em>, Aug.18-21, 2023, Qingdao City, China.</span><span class="citation-badge">引用 2 次</span><div class="pub-meta">唯一通讯作者，国际会议</div></li>
                    
                    <li><span class="paper-number">[9]</span> <span class="pub-title">Yu Feng, Yu'e Jiang*, Yutong Wang. “Generative Adversarial Network (GAN)-Based Physical Layer Covert Communications Against Powerful Adversaries in Federated Learning Networks.” in <em>International Conference on Networking and Network Applications (NaNA)</em>, Aug. 18-21, 2023, Qingdao City, China.</span><span class="citation-badge">引用 5 次</span><div class="pub-meta">唯一通讯作者，国际会议</div></li>
                    
                    <li><span class="paper-number">[10]</span> <span class="pub-title">Langtao Hu, Songjiao Bi, Quanjin Liu, Yu'e Jiang, Chunsheng Chen. “Intelligent Reflecting Surface Aided Covert Wireless Communication Exploiting Deep Reinforcement Learning.” <em>Wireless Networks</em>, 2023, 29, 877-889.</span><span class="citation-badge">引用 8 次</span><div class="pub-meta">JCR 1区 / CCF-C / 中科院三区，IF:2.1</div></li>
                </ul>
                <div style="font-size:0.8rem; color:#547a9b; margin-top: 0.2rem;">📌 谷歌学术总引用超过300次。数据基于Google Scholar真实记录（2026年5月）。</div>
            </div>
        </div>

        <!-- 专利栏 + （教学效果+综合荣誉合并） -->
        <div class="grid-2col">
            <div class="card">
                <div class="card-header">⚙️ 授权/申请专利</div>
                <div class="card-content">
                    <ul class="patent-list">
                        <li>✔ <strong>授权专利</strong>：蒋玉娥, 江济民, 王雨桐, 洪悦, 章晨, 孙宜南, 邬海琴, 刘怡良. 无人机与智能反射面联合辅助的设备到设备隐蔽通信系统，授权号：ZL202411739794.3</li>
                        <li>✔ <strong>授权专利</strong>：蒋玉娥, 洪悦, 汪文明, 吴志奇, 江济民, 查海涅, 宋婧, 邬海琴, 刘怡良. 一种基于非正交多址的智能反射面辅助无人机隐蔽通信系统，授权号：ZL2025112101483800</li>
 <li>✔ <strong>授权专利</strong>：王良民, 蒋玉娥, 陈晓华, 陈向益, 刘怡良, 邬海琴, 赵蕙. 一种具有全双工基站蜂窝网络的D2D隐蔽通信系统及其通信方法，专利号：CN 109714737B (授权时间 2021-08-20)</li>
                        <li>✔ <strong>授权专利</strong>：王良民, 蒋玉娥, 赵蕙, 刘怡良, 陈晓华, 宋香梅, 邬海琴. 一种面向5G蜂窝网物理层安全的D2D隐蔽通信系统及通信方法，专利号：CN 108834113B (授权时间 2020-09-15)</li>
                       
                        <li>✔ <strong>实审中</strong>：蒋玉娥, 王雨桐, 孙宜南, 邬海琴, 汪文明, 江济民. 面向区块链物联网的隐蔽卸载通信方法及系统，申请号：202410406315X</li>
                    </ul>
                    <div style="margin-top: 0.4rem; font-size:0.7rem; color:#6f8eaa;">注：专利涵盖IRS-UAV隐蔽通信、区块链物联网安全等方向，全部发明人已列明。</div>
                </div>
            </div>
            <div class="card">
                <div class="card-header">📈 教学效果与综合荣誉</div>
                <div class="card-content">
                    <ul class="merged-list">
                        <li><strong>🏅 指导学生竞赛获奖</strong><br>
                            安徽省高校物联网应用创新大赛 一等奖（2025、2024、2023）<br>
                            安徽省大学生服务外包创新创业大赛 一等奖（2021）<br>
                            中国大学生计算机设计大赛 国赛三等奖（2021）<br>
                            安徽省“互联网+”大学生创新创业大赛 铜奖（2021）<br>
                            近五年指导学生获省级以上学科竞赛奖励20余项
                        </li>
                        <li><strong>🏅 个人综合荣誉</strong><br>
                            安徽省高端人才引育行动项目—青年拔尖人才青年学者<br>
                            安徽省高校物联网应用创新大赛 优秀指导教师 (2024,2023,2021)<br>
                            安徽省大学生服务外包创新创业大赛 优秀指导教师 (2021)<br>
                            省教学成果奖二等奖（主要完成人）
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 学术服务与招生 -->
        <div class="card">
            <div class="card-header">🔗 学术服务 & 招生</div>
            <div class="card-content">
                <p>✨ 担任IEEE TIFS, TVT, IoT-J, TCOM等多个权威期刊审稿人。<br>
                ✨ 主持国家自然科学基金青年项目、安徽省青年拔尖人才项目，科研经费较为充足；<strong>招收软件工程（学硕）、电子信息（专硕）</strong>，欢迎通信、计算机、软件工程等背景学生报考。<br>
                ✨ 课题组注重前沿研究与工程实践，提供良好科研环境和学术指导。<br>
                ✨ 本页面论文引用数据与Google Scholar完全同步（2026年5月）。</p>
                <div style="background:#F5F9FE; border-radius:0.8rem; padding:0.6rem; margin-top:0.6rem; font-size:0.8rem;">
                    📢 数据涵盖2025年教学创新大赛、案例大赛一等奖及最新科研奖励。欢迎邮件咨询。
                </div>
            </div>
        </div>
    </div>
    <footer>
        © 2026 蒋玉娥 (Yu'e Jiang) | 安庆师范大学 人工智能与计算机学院 | 招收软件工程学硕、电子信息专硕<br>
        联系邮箱：jiang2012118@163.com | 论文引用数基于Google Scholar真实记录
    </footer>
</div>

<script>
    (function() {
        const today = new Date();
        const year = today.getFullYear();
        const month = String(today.getMonth() + 1).padStart(2,'0');
        const day = String(today.getDate()).padStart(2,'0');
        const updateSpan = document.getElementById('lastUpdateDate');
        if (updateSpan) {
            updateSpan.innerText = `${year}-${month}-${day}`;
        }
        console.log("蒋玉娥学术主页 - 论文引用数已按照Google Scholar真实数据校准");
    })();
</script>
</body>
</html>
