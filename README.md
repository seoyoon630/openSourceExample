## How To Add Custom Library To JitPack

1. Create Project

2. Create Module

3. Add classpath "com.github.dcendents:android-maven-gradle-plugin:${LATEST_VERSION}" in the project level build.gradle
 (Check Version : https://github.com/dcendents/android-maven-gradle-plugin/releases )
 (reference : https://developer.android.com/studio/build/maven-publish-plugin )

4. Add group = 'com.github.${YOUR_GITHUB_ID}' in the library level build.gradle

5. Draft a new release and create a new tag in Github 

6. Finishing Process with JitPack
  (JitPack : https://jitpack.io/ )
