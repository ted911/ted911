<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=36BCF7&center=true&vCenter=true&width=435&lines=Hi,+I'm+Ted911;Backend+System+Architect;Quality+%26+Automation+Specialist" alt="Typing SVG" />
</div>

<div align="center">
  <h3><i>"Building maintainable systems with robust automation."</i></h3>
</div>

<br />

<!-- BENTO GRID LAYOUT SIMULATION -->
<!-- GitHub Markdown doesn't support CSS Grid, so we use Tables for layout -->
<table align="center" border="0" cellpadding="0" cellspacing="0">
  <tr>
    <!-- CELL 1: TECH STACK -->
    <td width="50%" align="center" style="border: none;">
      <h3>🛠️ Core Engineering</h3>
      <br />
      <img src="https://skillicons.dev/icons?i=java,spring,mysql,gradle,hibernate&theme=dark" />
      <br /><br />
      <p><b>Spring Batch & Legacy Refactoring</b></p>
    </td>
    <!-- CELL 2: GITHUB STATS -->
    <td width="50%" align="center" style="border: none;">
       <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=ted911&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117" alt="stats graph" />
    </td>
  </tr>
  <tr>
    <!-- CELL 3: DEVOPS & INFRA -->
    <td width="50%" align="center" style="border: none;">
      <h3>🚀 Architecture & Ops</h3>
      <br />
      <img src="https://skillicons.dev/icons?i=docker,kubernetes,grafana,nginx,linux&theme=dark" />
      <br /><br />
      <p><b>K8s Deployment & Monitoring</b></p>
    </td>
    <!-- CELL 4: QUALITY & AUTOMATION -->
    <td width="50%" align="center" style="border: none;">
      <h3>🛡️ Quality Assurance</h3>
      <br />
      <p>
        <img src="https://img.shields.io/badge/Static_Analysis-SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white" />
        <img src="https://img.shields.io/badge/Workflow-n8n-FF6584?style=for-the-badge&logo=n8n&logoColor=white" />
      </p>
      <br />
      <p><b>Standardization & Policy Governance</b></p>
    </td>
  </tr>
</table>

<br />

<!-- TECH STACK SUMMARY SECTION -->
<h3 align="center">⚡ Engineering Tech Stack & Contributions</h3>

## 📱 Mobile & Frontend (React Native, React, TypeScript)

**Projects:** `eventu-app`, `eventu-webview`, `eventu-admin`

### React Native (`eventu-app`)

- **Navigation**: Implemented `RootNavigator`, `AuthNavigator`, and handled back button gestures (`useAndroidBackHandler`, `beforeRemove`).
- **Webview Integration**: Developed `WebviewScreen` for seamless hybrid app experiences.
- **Permissions & Notifications**: Managed App Permissions (`PermissionsGuideScreen`), Notification settings (`PushSettingScreen`), and Notifee integration.
- **Native Modules**: Configured Android (`grade`, `xml`) and iOS (`Podfile`, `Info.plist`, `xcodeproj`) settings.
- **Maintenance**: Implemented maintenance mode screens and modals.

### React Web & WebView (`eventu-webview`, `eventu-admin`)

- **UI/UX**:
  - Implemented complex UI components like Flip Cards (`FlipCard.tsx`), Hidden Cards, and Feed lists.
  - Used **Styled Components** (`.style.tsx`) and **CSS** for styling.
  - Integrated **Lottie** animations (`LottieHiddenCard.tsx`).
- **State Management & Querying**:
  - Extensive use of **React Query** (`usePointQuery`, `useMemberQuery`).
  - Custom Hooks (`useChart`, `useModal`, `useEventWrite`).
- **Features**:
  - **Dashboard**: Developed charts for DAU, App Downloads using charting libraries (`activeUsersChart`, `AppDownloadCountChart`).
  - **Event Management**: Created event writing flows (Step 1-4), Event Detail pages, and Report pages.
  - **Benefit/Point**: Attendance checks, Roulette/Drawing games (`Drawing.tsx`), Point History.

## ☕ Backend (Java, Spring Boot)

**Projects:** `eventu-point`, `eventu-batch`, `eventu-common-java`

### Java & Spring Boot

- **API Development**: Created Controllers (`PointController`, `AdminPointController`) and Services (`PointService`, `ProbabilityService`).
- **Batch Processing** (`eventu-batch`):
  - Implemented Spring Batch jobs for data aggregation (DAU, MAU, Point Ranking).
  - Configured Job definitions and Steps (`AggregatePointRankingConfig`).
- **Redis Integration**:
  - Used Redis Streams for event processing (`StreamKey`, `MemberSignUpMessage`).
  - Implemented Distributed Locking (`DistributedLockAop.java`).

### Database & Data Access

- **MyBatis**: Extensively used MyBatis for SQL mapping.
  - XML Mappers: `PointMapper.xml`, `PointDetailHistoryMapper.xml`, `GoogleAnalyticsDataMapper.xml`.
  - Dynamic SQL for reports and history tracking.
- **SQL**: Schema updates and migration scripts (`eventu-point.sql`, `pointRanking.sql`).

## 🛠 DevOps & Infrastructure

**Projects:** `eventu-app`, `eventu-webview`, `All`

- **CI/CD**:
  - Configured GitHub Actions workflows (`android.yaml`, `codePush.yml`, `release.yml`).
  - Implemented **Semantic Release** for automated versioning.
  - Managed **CodePush** deployments for React Native.
- **Monitoring & Analytics**:
  - Integrated **Google Analytics (GA4)** data collection and batch processing.
  - Set up **Firebase Performance** monitoring.
  - Configured **Sentry** for error tracking (`sentry.properties`).
- **Package Management**: Managed dependencies via `package.json`, `yarn.lock`.

## 🎨 Design & Assets

- **Assets**: Managed SVGs, PNGs, and internal icons (`ico_hidden_card_coin.svg`, `splash.mp4`).
- **Fonts**: Applied custom fonts (NotoSans).

<br />

<br />

<!-- FOOTER: TOP LANGUAGES & SNAKE -->
<!-- <div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ted911&layout=compact&theme=tokyonight&hide_border=true&langs_count=6&bg_color=0d1117" />
</div> -->

<!-- <br /> -->

<!-- SNAKE GAME ANIMATION (Requires GitHub Action setup) -->
<div align="center">
  <img src="https://raw.githubusercontent.com/ted911/ted911/output/github-contribution-grid-snake.svg" alt="snake animation" />
</div>
