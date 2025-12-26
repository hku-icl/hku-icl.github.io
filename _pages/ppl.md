---
layout: archive
permalink: /ppl/
author_profile: true
---
<style>
  .team-container {
    font-family: 'Helvetica Neue', Arial, sans-serif;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }
  
  .header {
    text-align: center;
    margin-bottom: 40px;
  }
  
  .header h1 {
    color: #24292e;
    font-size: 32px;
    font-weight: 600;
    padding-bottom: 12px;
    border-bottom: 3px solid #0366d6;
    display: inline-block;
  }
  
  .section-title {
    color: #24292e;
    font-size: 24px;
    font-weight: 600;
    margin: 40px 0 20px;
    padding-bottom: 8px;
    border-bottom: 2px solid #0366d6;
    display: flex;
    align-items: center;
  }
  
  .section-title::before {
    content: "✓";
    color: #0366d6;
    margin-right: 10px;
    font-size: 20px;
  }
  
  .team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
    gap: 20px;
    margin-bottom: 30px;
  }
  
  .team-card {
    background: white;
    border: 1px solid #e1e4e8;
    border-radius: 10px;
    padding: 15px;
    display: flex;
    transition: transform 0.2s, box-shadow 0.2s;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  }
  
  .team-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }
  
  .member-info {
    flex-grow: 1;
    padding-right: 15px;
  }
  
  .member-photo {
    flex-shrink: 0;
    width: 100px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  .member-photo img {
    width: 100px;
    height: 120px;
    object-fit: cover;
    border-radius: 6px;
    border: 1px solid #eaecef;
    margin-bottom: 8px;
  }
  
  .member-name {
    color: #24292e;
    font-size: 18px;
    font-weight: 600;
    margin: 0 0 8px 0;
  }
  
  .member-degree {
    color: #586069;
    font-size: 12px;
    line-height: 1.4;
    margin: 0 0 4px 0;
  }
  
  .member-interest {
    margin-top: 8px;
    padding-top: 8px;
    border-top: 1px solid #f1f1f1;
  }
  
  .interest-label {
    color: #24292e;
    font-size: 12px;
    font-weight: 600;
    margin: 0 0 4px 0;
  }
  
  .interest-content {
    color: #0366d6;
    font-size: 12px;
    line-height: 1.4;
    margin: 0;
  }
  
  .next-destination {
    margin-top: 6px;
    padding-top: 6px;
    border-top: 1px dashed #f1f1f1;
  }
  
  .destination-label {
    color: #24292e;
    font-size: 12px;
    font-weight: 600;
    margin: 0 0 4px 0;
  }
  
  .destination-content {
    color: #6a737d;
    font-size: 12px;
    margin: 0;
  }
  
  @media (max-width: 768px) {
    .team-grid {
      grid-template-columns: 1fr;
    }
    
    .team-card {
      flex-direction: column-reverse;
    }
    
    .member-info {
      padding-right: 0;
      padding-top: 15px;
    }
    
    .member-photo {
      width: 100%;
      align-items: center;
    }
    
    .member-photo img {
      width: 100px;
      height: 120px;
    }
  }
</style>

<div class="team-container">
  <div class="header">
    <h1>Meet Our Team</h1>
  </div>
  
  <!-- PostDoc Researcher Section -->
  <h2 class="section-title">PostDoc Researcher</h2>
  <div class="team-grid">
    
    <!-- Nuofan Mao -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Nuofan Mao</h3>
        <p class="member-degree">Ph.D@Imperial College London</p>
        <p class="member-degree">MSc@The University of Western Australia</p>
        <p class="member-degree">B.E.@Southwest University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Signal processing.</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/nuofan_mao.jpg?raw=true" alt="Nuofan Mao">
      </div>
    </div>
    
    <!-- Dongyan Sui -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Dongyan Sui</h3>
        <p class="member-degree">Ph.D@Fudan University</p>
        <p class="member-degree">MSc@Fudan University</p>
        <p class="member-degree">B.S.@Fudan University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Distributed learning, Signal Processing, Network science.</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/dongyan2026.jpg?raw=true" alt="Dongyan Sui">
      </div>
    </div>
    
  </div>
  
  <!-- PhD Students Section -->
  <h2 class="section-title">PhD Students</h2>
  <div class="team-grid">
    
    <!-- Jingreng Lei -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Jingreng Lei</h3>
        <p class="member-degree">Ph.D@The University of Hong Kong</p>
        <p class="member-degree">M.Phil.@The University of Hong Kong</p>
        <p class="member-degree">B.E@Sun Yat-sen University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Machine Learning, Optimization, Wireless Communication</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/jingreng.jpg?raw=true" alt="Jingreng Lei">
      </div>
    </div>
    
    <!-- Zhu Qing -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Zhu Qing</h3>
        <p class="member-degree">Ph.D@The University of Hong Kong</p>
        <p class="member-degree">MSc@Nanyang Technological University</p>
        <p class="member-degree">B.E@Bejing University of Aeronautics and Astronautics</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Integrated Circuit Design, Embodied AI, Wireless Communication</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/qingzhu.jpg?raw=true" alt="Zhu Qing">
      </div>
    </div>
    
    <!-- Zantian Zhao -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Zantian Zhao</h3>
        <p class="member-degree">Ph.D@The University of Hong Kong</p>
        <p class="member-degree">MSc@University of Michigan</p>
        <p class="member-degree">B.E@Nanjing University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Wireless Communication, Machine Learning, Signal Processing</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/zantian2026.jpg?raw=true" alt="Zantian Zhao">
      </div>
    </div>
    
    <!-- Yanzhe Li -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Yanzhe Li</h3>
        <p class="member-degree">M.Phil@The University of Hong Kong</p>
        <p class="member-degree">B.E@Nanjing University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Machine Learning, Wireless Communication, IoT, Edge Computing</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/yanzhe2026.png?raw=true" alt="Yanzhe Li">
      </div>
    </div>
    
    <!-- Zijian Yang -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Zijian Yang</h3>
        <p class="member-degree">Ph.D@University of Macau</p>
        <p class="member-degree">B.E@Jilin University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Wireless communication, optimization</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/zijian.jpg?raw=true" alt="Zijian Yang">
      </div>
    </div>
    
    <!-- Yu Ding -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Yu Ding</h3>
        <p class="member-degree">Ph.D@University of Macau</p>
        <p class="member-degree">B.E@Nankai University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Data science and machine learning, signal processing, IoT</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/yu.jpg?raw=true" alt="Yu Ding">
      </div>
    </div>
    
    <!-- Yewen Cao -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Yewen Cao</h3>
        <p class="member-degree">Ph.D@University of Macau</p>
        <p class="member-degree">B.E@Harbin Institute of Technology</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Wireless communications, signal processing, IoT</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/yewen.jpg?raw=true" alt="Yewen Cao">
      </div>
    </div>
    
    <!-- Enhao Chen -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Enhao Chen</h3>
        <p class="member-degree">Ph.D@University of Macau</p>
        <p class="member-degree">B.E@Harbin Institute of Technology</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">IoT, Cyberspace Security, Network topology.</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/Enhao.jpg?raw=true" alt="Enhao Chen">
      </div>
    </div>
    
    <!-- Hongyu AN -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Hongyu An</h3>
        <p class="member-degree">Ph.D@University of Macau</p>
        <p class="member-degree">MSc@Southern University of Science and Technology</p>
        <p class="member-degree">B.E@Harbin Institute of Technology</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Deep Learning, channel coding.</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/hongyu.jpg?raw=true" alt="Hongyu An">
      </div>
    </div>
    
    <!-- Dengke Wei -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Dengke Wei</h3>
        <p class="member-degree">Ph.D@University of Macau</p>
        <p class="member-degree">B.E@South China University of Technology</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Wireless Communications, optimization.</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/dengke.jpg?raw=true" alt="Dengke Wei">
      </div>
    </div>
    
    <!-- Huiji Jiao -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Huiji Jiao</h3>
        <p class="member-degree">Ph.D@University of Macau</p>
        <p class="member-degree">B.E@Harbin Institute of Technology</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Wireless Communications, optimization.</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/huiji.jpg?raw=true" alt="Huiji Jiao">
      </div>
    </div>
    
    <!-- Tianji He -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Tianji He</h3>
        <p class="member-degree">Ph.D@University of Macau</p>
        <p class="member-degree">B.E@Huazhong University of Science and Technology</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Wireless Communications, Artificial Intelligence.</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/tianji.png?raw=true" alt="Tianji He">
      </div>
    </div>
    
    <!-- Fan Yang -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Fan Yang</h3>
        <p class="member-degree">Ph.D@University of Macau</p>
        <p class="member-degree">MSc@University of Macau</p>
        <p class="member-degree">B.E@Nankai University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Information Theory, Artificial Intelligence.</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/fanyang2025.jpg?raw=true" alt="Fan Yang">
      </div>
    </div>
    
  </div>
  
  <!-- Visiting PhD Students Section -->
  <h2 class="section-title">Visiting PhD students</h2>
  <div class="team-grid">
    
    <!-- Menghan Li -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Menghan Li</h3>
        <p class="member-degree">Ph.D.@University of Chinese Academy of Sciences</p>
        <p class="member-degree">B.E@Wuhan University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Optical wireless communications, signal processing.</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/menghan.jpg?raw=true" alt="Menghan Li">
      </div>
    </div>
    
  </div>
  
  <!-- Alumni Section -->
  <h2 class="section-title">Alumni</h2>
  <div class="team-grid">
    
    <!-- Haotian Wu -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Haotian Wu</h3>
        <p class="member-degree">Ph.D.@Imperial College London</p>
        <p class="member-degree">MSc@Imperial College London</p>
        <p class="member-degree">B.E@Zhejiang University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Computer vision, communication, reinforcement learning, control theory.</p>
        </div>
        <div class="next-destination">
          <p class="destination-label">Next Destination:</p>
          <p class="destination-content">Imperial College London</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/haotian.jpg?raw=true" alt="Haotian Wu">
      </div>
    </div>
    
    <!-- Chenghong Bian -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Chenghong Bian</h3>
        <p class="member-degree">Ph.D.@Imperial College London</p>
        <p class="member-degree">MSc@University of Michigan</p>
        <p class="member-degree">B.E@Tsinghua University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Information theory, signal processing, semantic communications.</p>
        </div>
        <div class="next-destination">
          <p class="destination-label">Next Destination:</p>
          <p class="destination-content">Hong Kong University of Science and Technology</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/chenghong.png?raw=true" alt="Chenghong Bian">
      </div>
    </div>
    
    <!-- Runxin Zhang -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Runxin Zhang</h3>
        <p class="member-degree">Ph.D.@University of Chinese Academy of Sciences</p>
        <p class="member-degree">B.E@Nanjing University of Aeronautics and Astronautics</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Optical communications, signal processing.</p>
        </div>
        <div class="next-destination">
          <p class="destination-label">Next Destination:</p>
          <p class="destination-content">Tsinghua University</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/runxin.jpg?raw=true" alt="Runxin Zhang">
      </div>
    </div>
    
    <!-- Haoyang Di -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Haoyang Di</h3>
        <p class="member-degree">MSc@University of Electronic Science and Technology of China</p>
        <p class="member-degree">B.E@Zhengzhou University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Optimization.</p>
        </div>
        <div class="next-destination">
          <p class="destination-label">Next Destination:</p>
          <p class="destination-content">University of Bologna</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/haoyang_di.png?raw=true" alt="Haoyang Di">
      </div>
    </div>
    
    <!-- Pengfei Shen -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Pengfei Shen</h3>
        <p class="member-degree">Ph.D.@University of Chinese Academy of Sciences</p>
        <p class="member-degree">B.E@Xi'an Jiaotong University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Markov decision process, optical wireless communications, reconfigurable intelligent surface.</p>
        </div>
        <div class="next-destination">
          <p class="destination-label">Next Destination:</p>
          <p class="destination-content">航天九院704所</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/pengfei.png?raw=true" alt="Pengfei Shen">
      </div>
    </div>
    
    <!-- Chao Ji -->
    <div class="team-card">
      <div class="member-info">
        <h3 class="member-name">Chao Ji</h3>
        <p class="member-degree">Ph.D.@Southeast University</p>
        <p class="member-degree">B.E@Southeast University</p>
        <div class="member-interest">
          <p class="interest-label">Research interests:</p>
          <p class="interest-content">Wireless communication, channel coding, MIMO.</p>
        </div>
        <div class="next-destination">
          <p class="destination-label">Next Destination:</p>
          <p class="destination-content">The Hong Kong Polytechnic University</p>
        </div>
      </div>
      <div class="member-photo">
        <img src="https://github.com/lynshao/Lab.github.io/blob/master/images/chao_ji.png?raw=true" alt="Chao Ji">
      </div>
    </div>
    
  </div>
</div>













