# Tech Stack Summary for User `ted911`

This document summarizes the contributions of user `ted911` across the `eventu` workspace, categorized by technology stack.

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

---
*Generated based on git commit history analysis.*
