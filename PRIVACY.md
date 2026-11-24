개인정보처리방침 (Privacy Policy) — CalendarTaskPro

시행일 / Effective Date: 2026-11-24

애플리케이션 / Application: CalendarTaskPro (CalendarTaskPro_CS)

저장소 / Repository: https://www.google.com/search?q=https://github.com/school4i/CalendarTaskPro


[한국어] 개인정보처리방침

CalendarTaskPro(이하 "본 앱")는 사용자의 개인정보를 소중하게 생각하며, Google API 서비스 사용자 데이터 정책(Google API Services User Data Policy) 및 관련 개인정보 보호 기준을 준수합니다.

1. 수집 및 접근하는 정보

본 앱은 사용자가 직접 Google 캘린더 연동 기능을 실행하고 권한을 허용한 경우에만 아래 정보에 접근합니다.

Google 캘린더 데이터 (https://www.googleapis.com/auth/calendar): 사용자의 캘린더 목록 조회 및 일정(제목, 날짜, 시간, 설명)의 조회, 생성, 수정, 삭제를 위해 사용됩니다.

로컬 사용자 데이터: 사용자가 앱 내에서 직접 작성한 일정, 할 일, 스티커 메모, 주간 시간표, 디데이 카드, 앱 설정 정보.

2. 데이터 저장 및 처리 방식 (100% 로컬 저장)

본 앱은 별도의 개발자 서버를 운영하지 않습니다.

사용자의 모든 일정 및 동기화된 Google 캘린더 데이터는 외부 서버로 전송되지 않으며, 오직 사용자 본인의 Windows PC 내 로컬 데이터베이스(%AppData%\CalendarTaskPro_CS\data.db)에만 저장됩니다.

Google OAuth 2.0 인증 토큰 또한 외부로 전송되지 않고 사용자 PC의 로컬 폴더(%AppData%\CalendarTaskPro_CS\GoogleToken)에만 보관됩니다.

3. 네트워크 통신 범위

본 앱은 다음 두 가지 목적 외에는 어떠한 외부 통신도 수행하지 않습니다.

Google Calendar API 동기화: 사용자가 구글 계정을 연동한 경우, Google 공식 API 서버와 직접 일정을 동기화합니다.

최신 버전 업데이트 확인(선택 사항): GitHub Releases(github.com/school4i/CalendarTaskPro)에서 최신 버전 태그만 확인하며, 이 과정에서 어떠한 사용자 개인정보나 일정 데이터도 전송하지 않습니다.

4. 제3자 제공 및 제한된 사용 준수 (Limited Use)

본 앱은 Google API로부터 얻은 정보를 제3자에게 판매, 임대, 공유하거나 광고 목적으로 사용하지 않습니다.

본 앱은 Google 사용자 데이터를 인공지능(AI) 또는 머신러닝(ML) 모델 학습에 사용하지 않습니다.

본 앱이 Google API에서 수신한 정보의 사용 및 다른 앱으로의 전송은 제한된 사용(Limited Use) 요구사항을 포함한 Google API 서비스 사용자 데이터 정책을 준수합니다.

5. 데이터 삭제 및 연동 해제 방법

사용자는 언제든지 아래 방법으로 연동 및 저장된 데이터를 완전히 삭제할 수 있습니다.

앱 내 연동 해제: [환경 설정] 창에서 구글 연동 해제 버튼을 클릭하면 로컬에 저장된 인증 토큰이 즉시 삭제됩니다.

Google 계정 권한 철회: Google 계정 권한 관리 페이지에서 CalendarTaskPro의 접근 권한을 직접 취소할 수 있습니다.

로컬 데이터 완전 삭제: PC에서 %AppData%\CalendarTaskPro_CS 폴더를 삭제하면 모든 일정과 설정 데이터가 영구 삭제됩니다.

6. 문의처

개인정보 처리와 관련한 문의사항은 아래 연락처 또는 GitHub 저장소 이슈를 통해 문의해 주세요.

이메일: [colorstar2024@gmail.com]

GitHub Issues: https://www.google.com/search?q=https://github.com/school4i/CalendarTaskPro/issues

[English] Privacy Policy

CalendarTaskPro (the "App") respects your privacy and complies with the Google API Services User Data Policy.

1. Information We Access

The App accesses Google user data only when you explicitly choose to connect your Google Account and grant OAuth 2.0 permission:

Google Calendar Data (https://www.googleapis.com/auth/calendar): Used to retrieve your calendar list and to view, create, update, and delete calendar events (title, date, time, and description) directly between your desktop and Google Calendar.

Local User Data: Tasks, schedules, sticky notes, class timetables, countdown cards, and application preferences you create inside the App.

2. Data Storage and Processing (Local-Only Architecture)

The App does not operate any developer-hosted backend servers.

All tasks, notes, and synced Google Calendar events are stored strictly on your local Windows PC (%AppData%\CalendarTaskPro_CS\data.db).

Google OAuth 2.0 authorization tokens are stored locally on your device (%AppData%\CalendarTaskPro_CS\GoogleToken) and are never transmitted to the developer or any third party.

3. Network Communications

The App only communicates over the network for the following two purposes:

Google Calendar Synchronization: Communicates directly with Google's official Calendar API endpoints only when you authorize your Google Account.

Update Check (Optional): Checks the latest release version from GitHub Releases (github.com/school4i/CalendarTaskPro) without sending any personal or schedule data.

4. Data Sharing & Google API Limited Use Disclosure

We do not sell, rent, transfer, or share your Google Calendar data or personal information with any third parties or advertisers.

We do not use Google user data to train generalized AI or machine learning models.

CalendarTaskPro's use and transfer to any other app of information received from Google APIs will adhere to the Google API Services User Data Policy, including the Limited Use requirements.

5. Data Deletion and Revoking Access

You can revoke access and delete all stored data at any time:

Disconnect inside the App: Open Settings and click Disconnect Google to immediately delete your local OAuth token.

Revoke via Google Account: Visit your Google Account Permissions page and remove access for CalendarTaskPro.

Delete All Local Data: Delete the %AppData%\CalendarTaskPro_CS folder on your PC to remove all locally stored schedules, notes, and settings.

6. Contact Information

If you have any questions about this Privacy Policy, please contact us via:

Email: [colorstar2024@gmail.com]

GitHub Issues: https://www.google.com/search?q=https://github.com/school4i/CalendarTaskPro/issues
