---
layout: archive
permalink: /research/
author_profile: true
---

<style>
  .research-intro {
    max-width: 1000px;
    margin: 3rem auto;
    padding: 2rem;
    background: white;
    border-radius: 12px;
    box-shadow: 0 5px 20px rgba(0,0,0,0.08);
    position: relative;
  }
  
  .intro-quote {
    position: absolute;
    top: -15px;
    left: 40px;
    font-size: 5rem;
    color: #3949ab;
    opacity: 0.2;
    font-family: Georgia, serif;
    line-height: 1;
  }
  
  .research-intro p {
    color: #2c3e50;
    font-size: 1.1rem;
    line-height: 1.8;
    margin: 0 0 1.5rem 0;
    position: relative;
    z-index: 1;
  }
  
  .research-intro p:first-of-type {
    margin-top: 2rem;
  }
  
  .research-intro p:last-of-type {
    margin-bottom: 1rem;
  }
  
  .research-agenda-title {
    text-align: center;
    font-size: 2.5rem;
    font-weight: 700;
    margin: 4rem 0 3rem;
    color: #1a237e;
    position: relative;
  }
  
  .research-agenda-title:after {
    content: '';
    display: block;
    width: 100px;
    height: 4px;
    background: linear-gradient(90deg, #3949ab, #7986cb);
    margin: 1rem auto;
    border-radius: 2px;
  }
  
  .research-thrusts {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
    gap: 3rem;
    max-width: 1200px;
    margin: 0 auto 4rem;
  }
  
  .research-card {
    background: white;
    border-radius: 16px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(0,0,0,0.08);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    border: 1px solid #e8eaf6;
  }
  
  .research-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 15px 35px rgba(0,0,0,0.12);
  }
  
  .card-header {
    background: linear-gradient(135deg, #3949ab 0%, #283593 100%);
    color: white;
    padding: 2rem;
    position: relative;
  }
  
  .thrust-number {
    position: absolute;
    top: -25px;
    left: 30px;
    background: #ff4081;
    color: white;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5rem;
    font-weight: 700;
    box-shadow: 0 5px 15px rgba(255,64,129,0.3);
  }
  
  .card-title {
    font-size: 1.8rem;
    font-weight: 600;
    margin: 0 0 0.5rem 0;
  }
  
  .card-subtitle {
    font-size: 1rem;
    opacity: 0.9;
    font-weight: 300;
  }
  
  .card-content {
    padding: 2rem;
  }
  
  .research-description {
    color: #333;
    line-height: 1.7;
    margin-bottom: 2rem;
    font-size: 1rem;
  }
  
  .research-description.english {
    border-left: 3px solid #3949ab;
    padding-left: 1.2rem;
    margin-bottom: 2rem;
  }
  
  .research-description.chinese {
    border-left: 3px solid #ff4081;
    padding-left: 1.2rem;
    font-style: italic;
    color: #555;
    background: #f9f9f9;
    padding: 1.2rem;
    border-radius: 0 8px 8px 0;
  }
  
  .tech-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem;
    margin: 2rem 0;
  }
  
  .tech-tag {
    background: #e8eaf6;
    color: #3949ab;
    padding: 0.4rem 1.2rem;
    border-radius: 20px;
    font-size: 0.9rem;
    font-weight: 500;
    transition: all 0.3s ease;
  }
  
  .tech-tag:hover {
    background: #3949ab;
    color: white;
    transform: translateY(-2px);
  }
  
  .media-section {
    margin-top: 2.5rem;
    padding-top: 2rem;
    border-top: 1px solid #eee;
  }
  
  .media-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1.5rem;
    margin-top: 1rem;
  }
  
  .media-item {
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
    transition: transform 0.3s ease;
    background: white;
    position: relative;
    min-height: 200px;
  }
  
  .media-item:hover {
    transform: scale(1.03);
    box-shadow: 0 8px 25px rgba(0,0,0,0.15);
  }
  
  .media-item.video {
    aspect-ratio: 16/9;
    background: linear-gradient(135deg, #1a237e, #3949ab);
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    position: relative;
  }
  
  .video-container {
    width: 100%;
    height: 100%;
    position: relative;
  }
  
  .video-container video {
    width: 100%;
    height: 100%;
    object-fit: contain;
    background: #000;
    display: none;
  }
  
  .video-play-button {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background: rgba(255, 64, 129, 0.9);
    width: 70px;
    height: 70px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 2rem;
    cursor: pointer;
    transition: all 0.3s ease;
    border: none;
    outline: none;
    z-index: 2;
  }
  
  .video-play-button:hover {
    background: #ff4081;
    transform: translate(-50%, -50%) scale(1.1);
  }
  
  .media-item img {
    width: 100%;
    height: 100%;
    max-height: 300px;
    object-fit: contain; /* 改为contain以完整显示图片 */
    display: block;
    transition: transform 0.5s ease;
    background-color: #f8f9fa; /* 添加背景色填充空白区域 */
    padding: 10px; /* 添加内边距 */
  }
  
  .media-item:hover img {
    transform: scale(1.05);
  }
  
  .media-caption {
    padding: 1rem;
    font-size: 0.9rem;
    color: #666;
    text-align: center;
    border-top: 1px solid #eee;
    background: #f8f9fa;
  }
  
  @media (max-width: 768px) {
    .research-thrusts {
      grid-template-columns: 1fr;
      gap: 2rem;
    }
    
    .media-grid {
      grid-template-columns: 1fr;
    }
    
    .research-intro {
      margin: 2rem 1rem;
      padding: 1.5rem;
    }
    
    .intro-quote {
      left: 20px;
      font-size: 4rem;
    }
    
    .media-item img {
      max-height: 250px;
    }
  }
  
  @media (min-width: 769px) and (max-width: 1024px) {
    .research-thrusts {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="research-intro">
  <div class="intro-quote">"</div>
  
  <p>Communication is more than technology; it is a foundational pillar of human civilization. For decades, its evolution, from theory to the pervasive reality of 5G and WiFi, has been a triumph of science and engineering, a testament to the pioneers who built the invisible infrastructure of our modern world.</p>
  
  <p>That very success now invites a profound question: Has the era of fundamental innovation in communication passed? Some observe a mature field and suggest the core work is complete.</p>
  
  <p>We see a different reality. The discipline is not ending; it is entering its most critical phase. Like physics or mathematics, communication is a bedrock science. Its prior revolutions constructed the connected world we rely upon; its next evolution will enable and define the future itself.</p>
</div>

<h2 class="research-agenda-title">Our Research Agenda</h2>

<div class="research-thrusts">
  <!-- Research Thrust 1 -->
  <div class="research-card">
    <div class="thrust-number">01</div>
    <div class="card-header">
      <h3 class="card-title">Wireless as an Enabling Hub</h3>
      <div class="card-subtitle">The Digital Transformation Catalyst</div>
    </div>
    
    <div class="card-content">
      <div class="research-description english">
        Our first research thrust positions wireless communication as an enabling hub for tomorrow's key technologies. We design next-generation network architectures and transmission mechanisms to support cross-disciplinary applications. This includes: building efficient and reliable communication frameworks for distributed artificial intelligence; enabling real-time and stable networking for robotic swarms; developing low-latency, high-fidelity wireless links for brain-computer interfaces; and constructing large-scale sensing networks for planet-scale environmental monitoring. By deeply integrating communications with AI, robotics, and other cutting-edge fields, we help realize true digital transformation and intelligent advancement.
      </div>
      
      <div class="research-description chinese">
        我们的第一个主要研究方向，是让无线通信成为未来关键科技的"赋能中枢"。我们探索并设计下一代无线网络架构与传输机制，以支撑跨学科、跨领域的融合应用。包括：为分布式人工智能系统提供高效可靠的协同通信支持；为集群机器人系统实现实时、稳定的组网与控制；为脑机接口设备开发低延迟、高保真的无线传输方案；以及为实现全球尺度的高精度环境感知与监测构建大规模无线传感网络。通过通信与其他前沿科技的深度融合，我们助力多个行业实现数字化转型与智能化跨越。
      </div>
      
      <div class="tech-tags">
        <span class="tech-tag">Agent Communication</span>
        <span class="tech-tag">Distributed AI</span>
        <span class="tech-tag">AI Infrastructure</span>
        <span class="tech-tag">Robotic Swarms</span>
      </div>
      
      <div class="media-section">
        <div class="media-grid">
          <div class="media-item video">
            <div class="video-container">
              <video id="researchVideo1" controls style="width:100%; height:100%; object-fit: contain;">
                <source src="/images/research/video1.mp4" type="video/mp4">
              </video>
            </div>
            <div class="media-caption">研究演示视频</div>
          </div>
          
          <div class="media-item">
            <img src="/images/research/A2.png" alt="Research Image A2">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
        </div>
        
        <div class="media-grid">
          <div class="media-item">
            <img src="/images/research/A3.png" alt="Research Image A3">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
          <div class="media-item">
            <img src="/images/research/A4.png" alt="Research Image A4">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
        </div>
        
        <div class="media-grid">
          <div class="media-item">
            <img src="/images/research/A5.png" alt="Research Image A5">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
          <div class="media-item">
            <img src="/images/research/A7.png" alt="Research Image A6">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  
  <!-- Research Thrust 2 -->
  <div class="research-card">
    <div class="thrust-number">02</div>
    <div class="card-header">
      <h3 class="card-title">Wireless Evolution & Innovation</h3>
      <div class="card-subtitle">Pushing the Boundaries of Connectivity</div>
    </div>
    
    <div class="card-content">
      <div class="research-description english">
        Our second research thrust focuses on the evolution and innovation of wireless systems themselves. We aim to continuously increase data rates, approach near-zero latency, and ensure ultra-high reliability. On one hand, we enhance existing systems, such as 5G, WiFi, Bluetooth, and NB-IoT, through improved physical-layer techniques, protocol design, and network optimization. On the other, we pioneer new communication paradigms for extreme and emerging environments, including underground, underwater, space, and optical wireless communications, developing innovative solutions for connectivity where it was once thought impossible.
      </div>
      
      <div class="research-description chinese">
        我们的第二个主要研究方向，是无线通信系统本身的"演进与革新"。核心目标在于全面提升系统的传输速率、降低时延与抖动，并保障极高的通信可靠性。一方面，我们着力强化与完善现有通信体系，针对5G、WiFi、蓝牙、NB-IoT等主流标准与场景，研究更优的物理层技术、协议设计及网络优化方法；另一方面，我们也积极开拓面向未来的新型无线通信系统，涵盖透地通信、深海通信、深空通信以及无线光通信等极端或新兴信道环境，为解决特殊场景中的通信难题开发创新性技术。
      </div>
      
      <div class="tech-tags">
        <span class="tech-tag">6G</span>
        <span class="tech-tag">Wi-Fi</span>
        <span class="tech-tag">Extreme Environment Comms</span>
        <span class="tech-tag">Optical Wireless</span>
        <span class="tech-tag">Network Optimization</span>
      </div>
      
      <div class="media-section">
        <div class="media-grid">
          <div class="media-item">
            <img src="/images/research/B1.png" alt="Research Image B1">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
          
          <div class="media-item">
            <img src="/images/research/B2.jpg" alt="Research Image B2">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
        </div>
        
        <div class="media-grid">
          <div class="media-item">
            <img src="/images/research/B3.png" alt="Research Image B3">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
          
          <div class="media-item">
            <img src="/images/research/B4.png" alt="Research Image B4">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
        </div>
        
        <div class="media-grid">
          <div class="media-item">
            <img src="/images/research/B5.png" alt="Research Image B5">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
          
          <div class="media-item">
            <img src="/images/research/B6.JPG" alt="Research Image B6">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
        </div>
        
        <div class="media-grid">
          <div class="media-item">
            <img src="/images/research/B7.jpg" alt="Research Image B7">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
          
          <div class="media-item">
            <img src="/images/research/B8.png" alt="Research Image B8">
            <div class="media-caption"> <!-- CAPTION HERE --> </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<script>
  // Add Font Awesome icons if not already included
  if (!document.querySelector('link[href*="font-awesome"]')) {
    const link = document.createElement('link');
    link.rel = 'stylesheet';
    link.href = 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css';
    document.head.appendChild(link);
  }
  
  // Video play function
  function playVideo(videoId, button) {
    const video = document.getElementById(videoId);
    const videoContainer = button.parentElement.querySelector('.video-container');
    
    if (video) {
      // 显示视频元素
      video.style.display = 'block';
      
      // 隐藏播放按钮
      button.style.display = 'none';
      
      // 开始播放
      video.play().catch(function(error) {
        console.log("Video play failed:", error);
        // 如果自动播放失败，显示控制条
        video.controls = true;
        video.play();
      });
      
      // 当视频结束时，显示播放按钮
      video.onended = function() {
        video.style.display = 'none';
        button.style.display = 'flex';
        video.currentTime = 0; // 重置视频到开始
      };
      
      // 如果有错误，显示错误信息
      video.onerror = function() {
        console.log("Error loading video");
        // 显示错误信息
        button.innerHTML = '<i class="fas fa-exclamation-triangle"></i>';
        button.style.background = '#ff6b6b';
        setTimeout(function() {
          button.innerHTML = '<i class="fas fa-play"></i>';
          button.style.background = 'rgba(255, 64, 129, 0.9)';
          button.style.display = 'flex';
          video.style.display = 'none';
        }, 2000);
      };
    }
  }
  
  // 图片加载错误处理
  document.addEventListener('DOMContentLoaded', function() {
    const images = document.querySelectorAll('img');
    images.forEach(img => {
      img.onerror = function() {
        this.src = 'data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="400" height="300" viewBox="0 0 400 300"><rect width="400" height="300" fill="%23f0f0f0"/><text x="200" y="150" font-family="Arial" font-size="16" text-anchor="middle" fill="%23999">Image not found</text></svg>';
        this.alt = 'Image not found';
      };
    });
  });
  
  // Add scroll animation
  document.addEventListener('DOMContentLoaded', function() {
    const cards = document.querySelectorAll('.research-card');
    const intro = document.querySelector('.research-intro');
    
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.style.opacity = '1';
          entry.target.style.transform = 'translateY(0)';
        }
      });
    }, {
      threshold: 0.1
    });
    
    // Animate intro section
    intro.style.opacity = '0';
    intro.style.transform = 'translateY(20px)';
    intro.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
    
    setTimeout(() => {
      intro.style.opacity = '1';
      intro.style.transform = 'translateY(0)';
    }, 300);
    
    // Animate cards
    cards.forEach(card => {
      card.style.opacity = '0';
      card.style.transform = 'translateY(20px)';
      card.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
      observer.observe(card);
    });
    
    // Pause video when scrolling away
    const video = document.getElementById('researchVideo1');
    if (video) {
      const videoObserver = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
          if (!entry.isIntersecting && !video.paused) {
            video.pause();
            const playButton = entry.target.querySelector('.video-play-button');
            if (playButton) {
              video.style.display = 'none';
              playButton.style.display = 'flex';
              video.currentTime = 0;
            }
          }
        });
      }, {
        threshold: 0.1
      });
      
      videoObserver.observe(video.parentElement);
    }
  });
</script>

