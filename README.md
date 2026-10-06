<!-- ======================================================== -->
<!-- 🌊 HERO BANNER & IDENTITY                                -->
<!-- ======================================================== -->

<div align="center">
  <img src="assets/banner.gif" width="680" alt="Ocean Wave Banner" style="border-radius: 12px; max-width: 100%; box-shadow: 0 4px 20px rgba(56,189,248,0.25);" />

  <br/><br/>

  <h1>Nguyen Van Khanh <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Waving%20Hand.png" alt="Waving Hand" width="34" height="34" style="vertical-align: middle;" /></h1>

  <div align="center">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=2600&pause=900&color=38BDF8&center=true&vCenter=true&width=680&height=35&lines=Java+Backend+Engineer+%E2%9A%A1;Distributed+Systems+%26+Microservices+%F0%9F%8C%8A;Kafka+Event-Driven+Architecture+%F0%9F%9A%80;Redis+Distributed+Caching+%26+Locks+%F0%9F%94%A5;C%2B%2B+Algorithm+Optimization+%26+IoT+%F0%9F%A7%A9" alt="Typing SVG" />
  </div>

  <p>
    <sub>Final-year Software Engineering student @ <b>FPT University Hanoi</b> &middot; Backend Intern @ <b>VNPT Cloud</b></sub>
  </p>

  <p>
    <a href="mailto:vankhanhak54@gmail.com"><img src="https://img.shields.io/badge/Email-vankhanhak54%40gmail.com-0B192C?style=flat-square&logo=gmail&logoColor=38BDF8&labelColor=0B192C" alt="Gmail"/></a>
    <a href="https://github.com/Khanhnv26"><img src="https://img.shields.io/badge/GitHub-Khanhnv26-0B192C?style=flat-square&logo=github&logoColor=38BDF8&labelColor=0B192C" alt="GitHub"/></a>
    <a href="https://leetcode.com/u/KhanhLiteraturez/"><img src="https://img.shields.io/badge/LeetCode-KhanhLiteraturez-0B192C?style=flat-square&logo=leetcode&logoColor=FDBA74&labelColor=0B192C" alt="LeetCode"/></a>
    <img src="https://img.shields.io/badge/FPT_University-Final--year-06B6D4?style=flat-square&labelColor=0B192C" alt="FPT University"/>
    <img src="https://img.shields.io/badge/VNPT_Cloud-Intern-FDBA74?style=flat-square&labelColor=0B192C" alt="VNPT Cloud"/>
  </p>
</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=06B6D4&height=2" width="100%"/>

<!-- ======================================================== -->
<!-- ⚡ CORE ENGINEERING FOCUS                                 -->
<!-- ======================================================== -->

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/High%20Voltage.png" alt="High Voltage" width="28" height="28" style="vertical-align: middle;" /> Core Engineering Focus

Tập trung thiết kế và tối ưu **hệ thống phân tán có độ trễ thấp, thông lượng cao**. Kiến trúc các dịch vụ vi mô (Microservices) chịu tải tốt với **Spring Boot 3**, ứng dụng **Apache Kafka** cho mô hình Event-Driven, sử dụng **Redis distributed locks** để kiểm soát tranh chấp đồng thời và bảo đảm tính nhất quán của dữ liệu. Ngoài ra là khả năng lập trình phần cứng IoT và giải thuật tối ưu với **C++**.

<img src="https://capsule-render.vercel.app/api?type=rect&color=06B6D4&height=2" width="100%"/>

<!-- ======================================================== -->
<!-- 🛠 TECH STACK & TOOLING                                   -->
<!-- ======================================================== -->

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" alt="Tools" width="28" height="28" style="vertical-align: middle;" /> Tech Stack & Tooling

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <b>Backend & Distributed Systems</b><br/>
      <sub>Java 21 &middot; Spring Boot 3 &middot; Spring Cloud &middot; Hibernate &middot; Apache Kafka &middot; Redis &middot; C++</sub>
    </td>
    <td width="50%" valign="top">
      <b>Infrastructure & Databases</b><br/>
      <sub>Docker &middot; Kubernetes &middot; PostgreSQL &middot; MySQL &middot; SQL Server &middot; Git &middot; Linux</sub>
    </td>
  </tr>
</table>

<div align="center">
  <br/>
  <img src="https://skillicons.dev/icons?i=java,spring,kafka,redis,postgres,docker,kubernetes,cpp&theme=dark" alt="Core Tech Stack" />
</div>

<br/>
<img src="https://capsule-render.vercel.app/api?type=rect&color=06B6D4&height=2" width="100%"/>

<!-- ======================================================== -->
<!-- 🚀 FEATURED SYSTEMS & ARCHITECTURE                        -->
<!-- ======================================================== -->

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="28" height="28" style="vertical-align: middle;" /> Featured Systems

### ⭐ [Mini Waybill Platform](https://github.com/Khanhnv26/Mini-Waybill-Platform---VNPT-Cloud) (VNPT Cloud)
> *Nền tảng logistics & theo dõi vòng đời bưu kiện phân tán theo kiến trúc Microservices.*

* 🛡️ **Spring Cloud Gateway**: Xác thực tập trung với JWT, phân quyền RBAC và rate-limiting chống nghẽn dịch vụ.
* 🛰️ **Apache Kafka Event Bus**: Xử lý luồng sự kiện trạng thái đơn hàng bất đồng bộ giữa các microservices.
* 🔒 **Redis Distributed Locks**: Cơ chế khóa phân tán ngăn chặn triệt để race condition khi cập nhật vận đơn đồng thời.

```mermaid
flowchart LR
    C([Client]) --> G["Spring Cloud Gateway<br/>JWT &middot; Rate Limiting"]
    G --> P[Parcel Service]
    G --> T[Tracking Service]
    P -- events --> K{{Kafka Event Bus}}
    T -- events --> K
    K --> N[Event Consumers]
    P -.-> R[("Redis<br/>Distributed Locks")]
    P --> D[(Database)]
    classDef n fill:#0B192C,stroke:#38BDF8,stroke-width:2px,color:#E2E8F0;
    classDef accent fill:#0B192C,stroke:#FDBA74,stroke-width:2px,color:#FDBA74;
    class C,G,P,T,N,R,D n;
    class K accent;
```

<br/>

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🅿️ <a href="https://github.com/Khanhnv26/SmarkParkingIOT">Smart Parking IoT</a></h3>
      <sub>Hệ thống đỗ xe tự động, phát hiện không gian trống và cảnh báo cháy nổ độ trễ thấp từ cảm biến lên Cloud.</sub>
      <p>
        <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++"/>
        <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32"/>
        <img src="https://img.shields.io/badge/IoT_Cloud-38BDF8?style=flat-square" alt="IoT Cloud"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>⚙️ <a href="https://github.com/Khanhnv26/SWP391-QuanLyMayPhatDien-G1">Generator Management</a></h3>
      <sub>Hệ thống ERP quản lý tài sản máy phát điện (SWP391), bảo mật RBAC qua Servlet Filters và xử lý batch Excel.</sub>
      <p>
        <img src="https://img.shields.io/badge/Java_Servlet-ED8B00?style=flat-square" alt="Java"/>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"/>
        <img src="https://img.shields.io/badge/Apache_POI-D22128?style=flat-square" alt="POI"/>
      </p>
    </td>
  </tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=06B6D4&height=2" width="100%"/>

<!-- ======================================================== -->
<!-- 📊 ENGINEERING PROOF & ACTIVITY                           -->
<!-- ======================================================== -->

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" alt="Bar Chart" width="28" height="28" style="vertical-align: middle;" /> Engineering Activity & Proof of Work

<!-- GitHub Trophy Ribbon -->
<div align="center">
  <img src="https://trophy.ryglcloud.net/?username=Khanhnv26&theme=flat&no-frame=true&no-bg=true&margin-w=4" alt="GitHub Trophies" />
</div>

<br/>

<table width="100%">
  <tr>
    <td width="50%" align="center" valign="middle">
      <a href="https://leetcode.com/u/KhanhLiteraturez/">
        <img height="170" src="https://leetcard.jacoblin.cool/KhanhLiteraturez?theme=dark&font=Fira%20Code" alt="LeetCode Stats" />
      </a>
    </td>
    <td width="50%" align="center" valign="middle">
      <img height="170" src="https://github-readme-stats.vercel.app/api?username=Khanhnv26&show_icons=true&hide_border=true&bg_color=0B192C&title_color=38BDF8&icon_color=06B6D4&text_color=E2E8F0" alt="GitHub Stats" />
    </td>
  </tr>
</table>

<br/>

<!-- Contribution Snake Animation -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Khanhnv26/Khanhnv26/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Khanhnv26/Khanhnv26/output/github-contribution-grid-snake.svg"/>
    <img alt="Contribution Snake" src="https://raw.githubusercontent.com/Khanhnv26/Khanhnv26/output/github-contribution-grid-snake-dark.svg" width="100%"/>
  </picture>
</div>

<br/>
<img src="https://capsule-render.vercel.app/api?type=rect&color=06B6D4&height=2" width="100%"/>

<!-- ======================================================== -->
<!-- 🤝 FOOTER                                                -->
<!-- ======================================================== -->

<div align="center">
  <p>
    <sub>Designed with minimalism &bull; Built for high concurrency &bull; &copy; 2026 Nguyen Van Khanh</sub>
  </p>
</div>
