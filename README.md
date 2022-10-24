# PMDK-quickAPI
패치 파일 및 전체 repo 는 업데이트 예정입니다.

##PMDK 라이브러리 기반 object / object pool handling 을 사용하기 쉽도록 추가한 API 적용 패치파일입니다.


### 적용방법
https://github.com/pmem/pmdk/releases 링크에서 pmdk-1.12.1.tar.gz 파일을 시스템에 다운로드 받습니다.
압축을 풀고, patch 파일을 적용시켜주세요.

pmdk 폴더로 들어가서 make 및 make install 을 통해 라이브러리를 설치합니다.

이 때, error 코드 혹은 warning message 출력 시 대부분의 경우 필요한 라이브러리가 포함되어 있지 않아 생기는 에러입니다.
운영체제에 따라 필요한 라이브러리 패키지를 설치해주세요.

### 사용법
src/examples/libpmemobj 폴더 내에 examples 들이 들어가 있습니다.

API 의 상세 사용법은 계속하여 추가하겠습니다.
