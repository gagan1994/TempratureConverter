MyLibrarys
my first library which convert f-c

STEPS:
create a android project
file->new->new module->android library->finish
add files in library
in library gradle file 
  apply plugin: 'com.android.library'
  apply plugin: 'com.android.library'
  // Required plugin in library module
  apply plugin: 'com.github.dcendents.android-maven'
  // Replace nisrulz with <your_github_username>
  group='com.github.<userName>'

in app:gradle file add: apply plugin: 'com.github.dcendents.android-maven'
                            compile project(<lib name>)
in build.gradle(project) add :
        classpath 'com.github.dcendents:android-maven-gradle-plugin:2.0'
push code to git and create a relese version
got to https://jitpack.io and paste yout git hub account url 
  and you will be instructed what to do
