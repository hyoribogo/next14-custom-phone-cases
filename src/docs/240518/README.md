## 새로 알게 된 사실

- [react-dropzone](https://react-dropzone.js.org/): 파일을 드래그 앤 드롭 혹은 클릭으로 업로드할 때 유용한 라이브러리이다. 파일 유형과 크기를 제한할 수 있고, onDropAccepted, onDropRejected 등 이벤트를 통해 업로드 과정을 세부적으로 제어할 수 있다.
- [useTransition](https://ko.react.dev/reference/react/useTransition): UI를 차단하지 않고 상태를 업데이트 할 수 있다.
- [uploadthing](https://uploadthing.com/): 파일 업로드 기능을 쉽게 구현할 수 있도록 도와주는 라이브러리이다. 로컬 파일 시스템, Amazon S3, Google Cloud Storage 등 다양한 스토리지 옵션을 지원한다.
- [prisma](https://www.prisma.io/): 데이터베이스 액세스 및 관리를 위한 현대적인 ORM(Object-Relational Mapping) 도구이다. SQL 쿼리를 직접 작성하지 않고도 데이터베이스를 효율적으로 관리할 수 있다. `npx prisma studio`를 실행하면 데이터베이스를 쉽게 확인할 수 있다.
- [supabase](https://supabase.com/): 오픈 소스 데이터베이스 플랫폼으로, PostgreSQL을 기반으로 하며 실시간 웹 소켓 기능과 REST API를 제공한다. Firebase와 유사한 기능을 제공한다고 한다.
- prisma와 supabase 함께 사용: supabase 내에서 테이블을 생성해 pull 받을 수도 있고, 아니면 prisma 파일에서 직접 스키마를 작성해 push할 수도 있다.
- [sharp](): 고성능 이미지 프로세싱 라이브러리로, 이미지 포맷 변환, 리사이징, 회전, 크롭, 메타데이터 추출 등 다양한 옵션을 지원한다. 최신 버전은 next.js에 불안정하기 때문에 `npm i sharp@0.32.6`으로 설치해 사용하면 된다.
- page.tsx에서 notFound() 호출하면 notFound 페이지로 이동한다.
