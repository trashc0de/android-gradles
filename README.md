# android-gradles
a quick and dirty list of implementations and stuff i often use in gradle file and i'm f**king sick of googling. **Attention**: versions numbers may vary


**KAPT**

	apply plugin: 'kotlin-kapt'
  
   
**VIEWMODEL + LIVEDATA**

	implementation 'androidx.lifecycle:lifecycle-viewmodel:2.2.0'
	implementation 'androidx.lifecycle:lifecycle-livedata-ktx:2.2.0'


**TIMBER**

	implementation 'com.jakewharton.timber:timber:4.7.1'
    

**RETROFIT**

	implementation 'com.squareup.retrofit2:retrofit:2.7.0'
	implementation 'com.squareup.retrofit2:converter-gson:2.7.0'
	implementation 'com.squareup.retrofit2:converter-scalars:2.7.0'

    
**MATERIAL**

	implementation 'com.google.android.material:material:1.2.0-alpha04'


**COROUTINES**

	implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-core:1.3.3'

*Retrofit adapter*
	
	implementation 'com.jakewharton.retrofit:retrofit2-kotlin-coroutines-adapter:0.9.2'


*Kotlin extension*
	
	implementation 'androidx.lifecycle:lifecycle-viewmodel-ktx:2.2.0'


**ROOM**

	implementation "androidx.room:room-runtime:2.2.3"
	kapt "androidx.room:room-compiler:2.2.3"

**GLIDE**

	implementation 'com.github.bumptech.glide:glide:4.10.0'
	kapt 'com.github.bumptech.glide:compiler:4.10.0'

**ANKO COMMONS**

	implementation "org.jetbrains.anko:anko-commons:0.10.5"

**MATERIAL PROGRESS BAR**

	implementation 'me.zhanghai.android.materialprogressbar:library:1.6.1'