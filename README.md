# My_Error_Fix_List
만난 에러 해결 목록

------------
## AndroidStudio 에러들

### 1 namespace 에러
- 23_05_17 AndroidStudio를 새로 설치(Flamingo)
- 기존 프로젝트를 새로 만들려고 프로젝트 생성
- 다음과 같은 에러를 만남

'''
Failed to query the value of property 'namespace'.
Package Name not found in AndroidManifest.xml, and namespace not specified. Please specify a namespace for the generated R and BuildConfig        classes via android.namespace in the module's build.gradle file like so:

android {
    namespace 'com.example.namespace'
}
'''

#### - Solution : File - Project Structure -> Android Gradle Plugin Version(8.0.1)->7.4.2 (그나마 업데이트 전 최신버전)
