### Hi there 👋

<!--
**JulianLopez2709/JulianLopez2709** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

// Coroutine Lifecycle Scopes
    implementation("androidx.activity:activity-ktx:1.7.2")
    implementation("androidx.lifecycle:lifecycle-viewmodel-ktx:2.6.2")
    implementation("androidx.lifecycle:lifecycle-runtime-ktx:2.6.2")

// Navigation Components
//bottomNavigation -> menu
//fragment -> app:navGraph="nameNavigationItem (nav-graph), name="androidx.navigation.fragment.NavHostFragment"
val nav_version = "2.5.3"
implementation("androidx.navigation:navigation-fragment-ktx:$nav_version")
implementation("androidx.navigation:navigation-ui-ktx:$nav_version")

// Glide  with load into
implementation("com.github.bumptech.glide:glide:4.16.0")

//Dagger - Hilt
implementation("com.google.dagger:hilt-android:2.48")
kapt("com.google.dagger:hilt-android-compiler:2.48")

//coroutines
implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:1.6.0")
testImplementation("org.jetbrains.kotlinx:kotlinx-coroutines-test:1.6.0")

//implementation test
testImplementation("io.mockk:mockk:1.13.7")
testImplementation("androidx.arch.core:core-testing:2.2.0")//2.1.0

// Client OkHttpClient -> interceptor
// Retrofit  Build baseUrl client addConverterFactory build
implementation("com.squareup.retrofit2:retrofit:2.9.0")
implementation("com.squareup.retrofit2:converter-gson:2.9.0")
