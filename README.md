# La-Gala
mi  nuevo proyecto
 nombre de componente  = " ProjectCodeStyleConfiguration " >
  < code_scheme  name = " Proyecto "  versión = " 173 " >
    < codeStyleSettings  language = " XML " >
      < indentOptions >
        < option  name = " CONTINUATION_INDENT_SIZE "  value = " 4 " />
      </ indentOptions >
      < arreglo >
        < reglas >
          < sección >
            < regla >
              < partido >
                < Y >
                  < NAME > xmlns: android </ NAME >
                  < XML_ATTRIBUTE />
                  < XML_NAMESPACE > ^ $ </ XML_NAMESPACE >
                </ Y >
              </ partido >
            </ regla >
          </ sección >
          < sección >
            < regla >
              < partido >
                < Y >
                  < NOMBRE > xmlns:. * </ NOMBRE >
                  < XML_ATTRIBUTE />
                  < XML_NAMESPACE > ^ $ </ XML_NAMESPACE >
                </ Y >
              </ partido >
              < pedido > BY_NAME </ pedido >
            </ regla >
          </ sección >
          < sección >
            < regla >
              < partido >
                < Y >
                  < NOMBRE >. *: Id </ NOMBRE >
                  < XML_ATTRIBUTE />
                  < XML_NAMESPACE > http://schemas.android.com/apk/res/android </ XML_NAMESPACE >
                </ Y >
              </ partido >
            </ regla >
          </ sección >
          < sección >
            < regla >
              < partido >
                < Y >
                  < NOMBRE >. *: Nombre </ NOMBRE >
                  < XML_ATTRIBUTE />
                  < XML_NAMESPACE > http://schemas.android.com/apk/res/android </ XML_NAMESPACE >
                </ Y >
              </ partido >
            </ regla >
          </ sección >
          < sección >
            < regla >
              < partido >
                < Y >
                  < NAME > nombre </ NAME >
                  < XML_ATTRIBUTE />
                  < XML_NAMESPACE > ^ $ </ XML_NAMESPACE >
                </ Y >
              </ partido >
            </ regla >
          </ sección >
          < sección >
            < regla >
              < partido >
                < Y >
                  < NAME > estilo </ NAME >
                  < XML_ATTRIBUTE />
                  < XML_NAMESPACE > ^ $ </ XML_NAMESPACE >
                </ Y >
              </ partido >
            </ regla >
          </ sección >
          < sección >
            < regla >
              < partido >
                < Y >
                  < NOMBRE >. * </ NOMBRE >
                  < XML_ATTRIBUTE />
                  < XML_NAMESPACE > ^ $ </ XML_NAMESPACE >
                </ Y >
              </ partido >
              < pedido > BY_NAME </ pedido >
            </ regla >
          </ sección >
          < sección >
            < regla >
              < partido >
                < Y >
                  < NOMBRE >. * </ NOMBRE >
                  < XML_ATTRIBUTE />
                  < XML_NAMESPACE > http://schemas.android.com/apk/res/android </ XML_NAMESPACE >
                </ Y >
              </ partido >
              < pedido > ANDROID_ATTRIBUTE_ORDER </ pedido >
            </ regla >
          </ sección >
          < sección >
            < regla >
              < partido >
                < Y >
                  < NOMBRE >. * </ NOMBRE >
                  < XML_ATTRIBUTE />
                  < XML_NAMESPACE >. * </ XML_NAMESPACE >
                </ Y >
              </ partido >
              < pedido > BY_NAME </ pedido >
            </ regla >
          </ sección >
        </ reglas >
      </ arreglo >
    </ codeStyleSettings >
  </ code_scheme >
</ componente > 
 20  .idea / gradle.xml 
@@ -0,0 +1,20 @@
<? xml versión = " 1.0 " codificación = " UTF-8 " ?>
< versión del proyecto  = " 4 " >
  < nombre de componente  = " GradleSettings " >
    < option  name = " linkedExternalProjectsSettings " >
      < GradleProjectSettings >
        < option  name = " testRunner "  value = " PLATFORM " />
        < option  name = " distributionType "  value = " DEFAULT_WRAPPED " />
        < option  name = " externalProjectPath "  value = " $ PROJECT_DIR $ " />
        < option  name = " gradleJvm "  value = " 1.8 " />
        < option  name = " módulos " >
          < conjunto >
            < option  value = " $ PROJECT_DIR $ " />
            < option  value = " $ PROJECT_DIR $ / app " />
          </ set >
        </ opción >
        < option  name = " resolveModulePerSourceSet "  value = " false " />
      </ GradleProjectSettings >
    </ opción >
  </ componente >
</ proyecto > 
 25  .idea / jarRepositories.xml 
@@ -0,0 +1,25 @@
<? xml versión = " 1.0 " codificación = " UTF-8 " ?>
< versión del proyecto  = " 4 " >
  < nombre de componente  = " RemoteRepositoriesConfiguration " >
    < repositorio-remoto >
      < option  name = " id "  value = " central " />
      < option  name = " name "  value = " Repositorio central de Maven " />
      < option  name = " url "  value = " https://repo1.maven.org/maven2 " />
    </ repositorio-remoto >
    < repositorio-remoto >
      < option  name = " id "  value = " jboss.community " />
      < option  name = " name "  value = " Repositorio de la comunidad JBoss " />
      < option  name = " url "  value = " https://repository.jboss.org/nexus/content/repositories/public/ " />
    </ repositorio-remoto >
    < repositorio-remoto >
      < option  name = " id "  value = " BintrayJCenter " />
      < option  name = " name "  value = " BintrayJCenter " />
      < option  name = " url "  value = " https://jcenter.bintray.com/ " />
    </ repositorio-remoto >
    < repositorio-remoto >
      < option  name = " id "  value = " Google " />
      < option  name = " name "  value = " Google " />
      < option  name = " url "  value = " https://dl.google.com/dl/android/maven2/ " />
    </ repositorio-remoto >
  </ componente >
</ proyecto > 
 9  .idea / misc.xml 
@@ -0,0 +1,9 @@
<? xml versión = " 1.0 " codificación = " UTF-8 " ?>
< versión del proyecto  = " 4 " >
  < nombre de componente  = " ProjectRootManager " versión = " 2 " languageLevel = " JDK_1_7 " project-jdk-name = " 1.8 " project-jdk-type = " JavaSDK " >    
    < url de salida  = " file: // $ PROJECT_DIR $ / build / classes " />
  </ componente >
  < nombre de componente  = " Tipo de proyecto " >
    < option  name = " id "  value = " Android " />
  </ componente >
</ proyecto > 
 6  .idea / render.experimental.xml 
@@ -0,0 +1,6 @@
<? xml versión = " 1.0 " codificación = " UTF-8 " ?>
< versión del proyecto  = " 4 " >
  < nombre de componente  = " RenderSettings " >
    < option  name = " showDecorations "  value = " true " />
  </ componente >
</ proyecto > 
 12  .idea / runConfigurations.xml 
@@ -0,0 +1,12 @@
<? xml versión = " 1.0 " codificación = " UTF-8 " ?>
< versión del proyecto  = " 4 " >
  < nombre de componente  = " RunConfigurationProducerService " >
    < option  name = " ignoredProducers " >
      < conjunto >
        < option  value = " org.jetbrains.plugins.gradle.execution.test.runner.AllInPackageGradleConfigurationProducer " />
        < option  value = " org.jetbrains.plugins.gradle.execution.test.runner.TestClassGradleConfigurationProducer " />
        < option  value = " org.jetbrains.plugins.gradle.execution.test.runner.TestMethodGradleConfigurationProducer " />
      </ set >
    </ opción >
  </ componente >
</ proyecto > 
 1  aplicación / .gitignore 
@@ -0,0 +1 @@
/ construir 
 33  app / build.gradle 
@@ -0,0 +1,33 @@
aplicar complemento : ' com.android.application '

android {
    compileSdkVersion 30
    buildToolsVersion " 30.0.1 "

    defaultConfig {
        applicationId " com.bpsound18.petagram "
        minSdkVersion 24
        targetSdkVersion 30
        versionCode 1
        versionName " 1.0 "

        testInstrumentationRunner " androidx.test.runner.AndroidJUnitRunner "
    }

    buildTypes {
        lanzamiento {
            minifyEnabled falso
            proguardFiles getDefaultProguardFile ( ' proguard-android-Optimize.txt ' ), ' proguard-rules.pro '
        }
    }
}

dependencias {
    implementación fileTree ( dir : " libs " , incluye : [ " * .jar " ])
    implementación ' androidx.appcompat: appcompat: 1.1.0 '
    implementación ' androidx.constraintlayout: constraintlayout: 1.1.3 '
    testImplementation ' junit: junit: 4.12 '
    androidTestImplementation ' androidx.test.ext: junit: 1.1.1 '
    androidTestImplementation ' androidx.test.espresso: espresso-core: 3.2.0 '

} 
 21  app / proguard-rules.pro 
@@ -0,0 +1,21 @@
# Agregue aquí reglas ProGuard específicas del proyecto.
# Puede controlar el conjunto de archivos de configuración aplicados utilizando el
# configuración de proguardFiles en build.gradle.
#
# Para obtener más detalles, consulte
# http://developer.android.com/guide/developing/tools/proguard.html

# Si su proyecto usa WebView con JS, descomente lo siguiente
# y especifique el nombre de clase completamente calificado para la interfaz de JavaScript
# clase:
# -keepclassmembers class fqcn.of.javascript.interface.for.webview {
# público *;
#}

# Descomente esto para conservar la información del número de línea para
# depuración de seguimientos de pila.
# -keepattributes SourceFile, LineNumberTable

# Si conserva la información del número de línea, descomente esto para
# ocultar el nombre del archivo fuente original.
# -renamesourcefileattribute SourceFile 
 26  app / src / androidTest / java / com / bpsound18 / petagram / ExampleInstrumentedTest.java 
@@ -0,0 +1,26 @@
paquete  com.bpsound18.petagram ;

importar  android.content.Context ;

importar  androidx.test.platform.app.InstrumentationRegistry ;
importar  androidx.test.ext.junit.runners.AndroidJUnit4 ;

import  org.junit.Test ;
import  org.junit.runner.RunWith ;

importar  org.junit.Assert estático . * ;

/ **
 * Prueba instrumentada, que se ejecutará en un dispositivo Android.
 *
* @See < un  href = " http://d.android.com/tools/testing " > Pruebas de documentación </a>
 * /
@RunWith ( clase AndroidJUnit4 . )
 clase  pública ExampleInstrumentedTest {
    @Prueba
    public  void  useAppContext () {
        // Contexto de la aplicación bajo prueba.
        Contexto appContext =  InstrumentationRegistry . getInstrumentation () . getTargetContext ();
        assertEquals ( " com.bpsound18.petagram " , appContext . getPackageName ());
    }
} 
 21  app / src / main / AndroidManifest.xml 
@@ -0,0 +1,21 @@
<? xml versión = " 1.0 " encoding = " utf-8 " ?>
< manifiesto  xmlns : android = " http://schemas.android.com/apk/res/android "
    paquete = " com.bpsound18.petagram " >

    < aplicación
        android : allowBackup = " true "
        android : icon = " @ mipmap / ic_launcher "
        android : label = " @ string / app_name "
        android : roundIcon = " @ mipmap / ic_launcher_round "
        android : supportsRtl = " true "
        android : theme = " @ style / AppTheme " >
        < actividad  android : name = " .MainActivity " >
            < filtro de intención >
                < acción  android : name = " android.intent.action.MAIN " />

                < categoría  android : name = " android.intent.category.LAUNCHER " />
            </ intent-filter >
        </ actividad >
    </ aplicación >

</ manifiesto > 
 14  app / src / main / java / com / bpsound18 / petagram / MainActivity.java 
@@ -0,0 +1,14 @@
paquete  com.bpsound18.petagram ;

importar  androidx.appcompat.app.AppCompatActivity ;

importar  android.os.Bundle ;

público  de clase  MainActivity  extiende  AppCompatActivity {

    @Anular
    protected  void  onCreate ( Bundle  SavedInstanceState ) {
        super . onCreate (SavedInstanceState);
        setContentView ( R . diseño . activity_main);
    }
} 
 30  aplicación / src / main / res / drawable-v24 / ic_launcher_foreground.xml 
@@ -0,0 +1,30 @@
< vector  xmlns : android = " http://schemas.android.com/apk/res/android "
    xmlns : aapt = " http://schemas.android.com/aapt "
    android : ancho = " 108dp "
    android : altura = " 108dp "
    android : viewportWidth = " 108 "
    android : viewportHeight = " 108 " >
    < ruta  android : pathData = " M31,63.928c0,0 6.4, -11 12.1, -13.1c7.2, -2.6 26, -1.4 26, -1.4l38.1,38.1L107,108.928l-32, -1L31, 63,928z " >
        < aapt : attr  name = " android: fillColor " >
            < gradiente
                android : endX = " 85.84757 "
                android : endY = " 92.4963 "
                android : startX = " 42.9492 "
                android : startY = " 49.59793 "
                android : type = " linear " >
                < artículo
                    android : color = " # 44000000 "
                    android : offset = " 0.0 " />
                < artículo
                    android : color = " # 00000000 "
                    android : offset = " 1.0 " />
            </ gradiente >
        </ aapt : attr >
    </ ruta >
    < camino
        android : fillColor = " #FFFFFF "
        android : fillType = " nonZero "
        android : pathData = " M65.3,45.828l3.8, -6.6c0.2, -0.4 0.1, -0.9 -0.3, -1.1c-0.4, -0.2 -0.9, -0.1 -1.1,0.3l-3.9, 6.7c-6.3, -2.8 -13.4, -2.8 -19.7,0l-3.9, -6.7c-0.2, -0.4 -0.7, -0.5 -1.1, -0.3C38.8,38.328 38.7,38.828 38.9,39.228l3. 8,6.6C36.2,49.428 31.7,56.028 31,63.928h46C76.3,56.028 71.8,49.428 65.3,45.828zM43.4,57.328c-0.8,0 -1.5, -0.5 -1.8, -1.2c-0.3, - 0.7 -0.1, -1.5 0.4, -2.1c0.5, -0.5 1.4, -0.7 2.1, -0.4c0.7,0.3 1.2,1 1.2,1.8C45.3,56.528 44.5,57.328 43.4,57.328L43.4, 57.328zM64.6,57.328c-0.8,0 -1.5, -0.5 -1.8, -1.2s-0.1, -1.5 0.4, -2.1c0.5, -0.5 1.4, -0.7 2.1, -0.4c0.7,0.3 1.2,1 1.2,1.8C66.5,56.528 65.6,57.328 64.6,57.328L64.6,57.328z "
        android : strokeWidth = " 1 "
        android : strokeColor = " # 00000000 " />
</ vector > 
 170  app / src / main / res / drawable / ic_launcher_background.xml 
@@ -0,0 +1,170 @@
<? xml versión = " 1.0 " encoding = " utf-8 " ?>
< vector  xmlns : android = " http://schemas.android.com/apk/res/android "
    android : ancho = " 108dp "
    android : altura = " 108dp "
    android : viewportWidth = " 108 "
    android : viewportHeight = " 108 " >
    < camino
        android : fillColor = " # 3DDC84 "
        android : pathData = " M0,0h108v108h-108z " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M9,0L9,108 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M19,0L19,108 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M29,0L29,108 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M39,0L39,108 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M49,0L49,108 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M59,0L59,108 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M69,0L69,108 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M79,0L79,108 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M89,0L89,108 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M99,0L99,108 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M0,9L108,9 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M0,19L108,19 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M0,29L108,29 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M0,39L108,39 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M0,49L108,49 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M0,59L108,59 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M0,69L108,69 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M0,79L108,79 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M0,89L108,89 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M0,99L108,99 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M19,29L89,29 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M19,39L89,39 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M19,49L89,49 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M19,59L89,59 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M19,69L89,69 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M19,79L89,79 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M29,19L29,89 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M39,19L39,89 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M49,19L49,89 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M59,19L59,89 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M69,19L69,89 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
    < camino
        android : fillColor = " # 00000000 "
        android : pathData = " M79,19L79,89 "
        android : strokeWidth = " 0.8 "
        android : strokeColor = " # 33FFFFFF " />
</ vector >
 18  aplicación / src / main / res / layout / activity_main.xml 
@@ -0,0 +1,18 @@
<? xml versión = " 1.0 " encoding = " utf-8 " ?>
< androidx .constraintlayout.widget.ConstraintLayout xmlns : android = " http://schemas.android.com/apk/res/android "
    xmlns : app = " http://schemas.android.com/apk/res-auto "
    xmlns : tools = " http://schemas.android.com/tools "
    android : layout_width = " match_parent "
    android : layout_height = " match_parent "
    herramientas : context = " .MainActivity " >

    < TextView
        android : layout_width = " wrap_content "
        android : layout_height = " wrap_content "
        android : text = " ¡Hola mundo! "
        aplicación : layout_constraintBottom_toBottomOf = " parent "
        aplicación : layout_constraintLeft_toLeftOf = " parent "
        aplicación : layout_constraintRight_toRightOf = " parent "
        aplicación : layout_constraintTop_toTopOf = " parent " />

</ androidx .constraintlayout.widget.ConstraintLayout> 
 5  aplicación / src / main / res / mipmap-anydpi-v26 / ic_launcher.xml 
@@ -0,0 +1,5 @@
<? xml versión = " 1.0 " encoding = " utf-8 " ?>
< adaptive-icon  xmlns : android = " http://schemas.android.com/apk/res/android " >
    < background  android : drawable = " @ drawable / ic_launcher_background " />
    < primer plano  android : drawable = " @ drawable / ic_launcher_foreground " />
</ adaptive-icon > 
 5  aplicación / src / main / res / mipmap-anydpi-v26 / ic_launcher_round.xml 
@@ -0,0 +1,5 @@
<? xml versión = " 1.0 " encoding = " utf-8 " ?>
< adaptive-icon  xmlns : android = " http://schemas.android.com/apk/res/android " >
    < background  android : drawable = " @ drawable / ic_launcher_background " />
    < primer plano  android : drawable = " @ drawable / ic_launcher_foreground " />
</ adaptive-icon > 
 BIN +3.51 KB app / src / main / res / mipmap-hdpi / ic_launcher.png 
No se muestra el archivo binario.
 BIN +5.21 KB app / src / main / res / mipmap-hdpi / ic_launcher_round.png 
No se muestra el archivo binario.
 BIN +2.57 KB app / src / main / res / mipmap-mdpi / ic_launcher.png 
No se muestra el archivo binario.
 BIN +3.31 KB app / src / main / res / mipmap-mdpi / ic_launcher_round.png 
No se muestra el archivo binario.
 BIN +4.81 KB app / src / main / res / mipmap-xhdpi / ic_launcher.png 
No se muestra el archivo binario.
 BIN +7,3 KB aplicación / src / main / res / mipmap-xhdpi / ic_launcher_round.png 
No se muestra el archivo binario.
 BIN +7.72 KB app / src / main / res / mipmap-xxhdpi / ic_launcher.png 
No se muestra el archivo binario.
 BIN +11,6 KB app / src / main / res / mipmap-xxhdpi / ic_launcher_round.png 
No se muestra el archivo binario.
 BIN +10.4 KB app / src / main / res / mipmap-xxxhdpi / ic_launcher.png 
No se muestra el archivo binario.
 BIN +16.2 KB app / src / main / res / mipmap-xxxhdpi / ic_launcher_round.png 
No se muestra el archivo binario.
 7  aplicación / src / main / res / values ​​/ colors.xml 
@@ -0,0 +1,7 @@
<? xml versión = " 1.0 " encoding = " utf-8 " ?>
< recursos >
    < color  name = " colorPrimary " > # 66DDE4 </ color >
    < color  name = " colorPrimaryDark " > # 3C2F33 </ color >
    < color  name = " colorAccent " > # E83B35 </ color >
    < color  name = " títulos " > #FFFFFF </ color >
</ recursos > 
 3  aplicación / src / main / res / values ​​/ strings.xml 
@@ -0,0 +1,3 @@
< recursos >
    < string  name = " app_name " > Petagram </ string >
</ recursos > 
 10  aplicación / src / main / res / values ​​/ styles.xml 
@@ -0,0 +1,10 @@
< recursos >
    <! - Tema de la aplicación base. ->
    < style  name = " AppTheme "  parent = " Theme.AppCompat.Light.DarkActionBar " >
        <! - Personaliza tu tema aquí. ->
        < item  name = " colorPrimary " > @ color / colorPrimary </ item >
        < item  name = " colorPrimaryDark " > @ color / colorPrimaryDark </ item >
        < item  name = " colorAccent " > @ color / colorAccent </ item >
    </ estilo >

</ recursos > 
 17  app / src / test / java / com / bpsound18 / petagram / ExampleUnitTest.java 
@@ -0,0 +1,17 @@
paquete  com.bpsound18.petagram ;

import  org.junit.Test ;

importar  org.junit.Assert estático . * ;

/ **
 * Ejemplo de prueba de unidad local, que se ejecutará en la máquina de desarrollo (host).
 *
* @See < un  href = " http://d.android.com/tools/testing " > Pruebas de documentación </a>
 * /
 clase  pública ExampleUnitTest {
    @Prueba
    public  void  added_isCorrect () {
        asertEquals ( 4 , 2  +  2 );
    }
} 
 24  build.gradle 
@@ -0,0 +1,24 @@
// Archivo de compilación de nivel superior donde puede agregar opciones de configuración comunes a todos los subproyectos / módulos.
buildscript {
    repositorios {
        google ()
        jcenter ()
    }
    dependencias {
        classpath " com.android.tools.build:gradle:4.0.1 "

        // NOTA: No coloque las dependencias de su aplicación aquí; ellos pertenecen
        // en los archivos build.gradle del módulo individual
    }
}

allprojects {
    repositorios {
        google ()
        jcenter ()
    }
}

tarea de limpieza ( tipo : Eliminar ) {
    eliminar rootProject . buildDir
} 
 19  gradle.properties 
@@ -0,0 +1,19 @@
# Configuración de Gradle en todo el proyecto.
# Usuarios de IDE (por ejemplo, Android Studio):
# La configuración de Gradle configurada a través del IDE * anulará *
# cualquier configuración especificada en este archivo.
# Para obtener más detalles sobre cómo configurar su entorno de compilación, visite
# http://www.gradle.org/docs/current/userguide/build_environment.html
# Especifica los argumentos de JVM utilizados para el proceso del demonio.
# La configuración es particularmente útil para ajustar la configuración de la memoria.
org.gradle.jvmargs = -Xmx2048m
# Cuando esté configurado, Gradle se ejecutará en modo paralelo de incubación.
# Esta opción solo debe usarse con proyectos desacoplados. Más detalles, visite
# http://www.gradle.org/docs/current/userguide/multi_project_builds.html#sec:decoupled_projects
# org.gradle.parallel = true
# Estructura del paquete AndroidX para aclarar qué paquetes se incluyen con
# Sistema operativo Android, y que están empaquetados con el APK de tu aplicación
# https://developer.android.com/topic/libraries/support-library/androidx-rn
android.useAndroidX = true
# Convierta automáticamente bibliotecas de terceros para usar AndroidX
android.enableJetifier = true 
 BIN +53,1 KB gradle / wrapper / gradle-wrapper.jar 
No se muestra el archivo binario.
 6  gradle / wrapper / gradle-wrapper.properties 
@@ -0,0 +1,6 @@
# Dom 26 de julio 21:37:50 COT 2020
distributionBase = GRADLE_USER_HOME
distributionPath = envoltorio / dists
zipStoreBase = GRADLE_USER_HOME
zipStorePath = envoltorio / dists
distributionUrl = https \: //services.gradle.org/distributions/gradle-6.1.1-all.zip
 172  gradlew 
@@ -0,0 +1,172 @@
#! / usr / bin / env sh

# ############################################## ###########################
# #
# # Script de inicio de Gradle para UN * X
# #
# ############################################## ###########################

# Intente configurar APP_HOME
# Resolver enlaces: $ 0 puede ser un enlace
PRG = " $ 0 "
# Necesita esto para enlaces simbólicos relativos.
mientras que [ -h  " $ PRG " ] ;  hacer
    ls = ` ls -ld " $ PRG " `
    enlace = ` expr " $ ls "  :  ' . * -> \ (. * \) $ ' `
    if expr " $ enlace "  :  ' /.* '  > / dev / null ;  luego
        PRG = " $ enlace "
    más
        PRG = ` dirname " $ PRG " ` " / $ enlace "
    fi
hecho
GUARDADO = " ` pwd ` "
cd  " ` dirname \ " $ PRG \" ` / "  > / dev / null
APP_HOME = " ` pwd -P ` "
cd  " $ GUARDADO "  > / dev / null

APP_NAME = " Gradle "
APP_BASE_NAME = ` nombre base " $ 0 " `

# Agregue aquí las opciones predeterminadas de JVM. También puede utilizar JAVA_OPTS y GRADLE_OPTS para pasar las opciones de JVM a este script.
DEFAULT_JVM_OPTS = " "

# Use el máximo disponible, o configure MAX_FD! = -1 para usar ese valor.
MAX_FD = " máximo "

advertir () {
    echo  " $ * "
}

morir () {
    eco
    echo  " $ * "
    eco
    salida 1
}

# Soporte específico del sistema operativo (debe ser 'verdadero' o 'falso').
cygwin = falso
msys = falso
darwin = falso
nonstop = falso
caso  " ` uname ` "  en
  CYGWIN * )
    cygwin = verdadero
    ;;
  Darwin * )
    darwin = verdadero
    ;;
  MINGW * )
    msys = verdadero
    ;;
  SIN PARAR * )
    sin parar = verdadero
    ;;
esac

CLASSPATH = $ APP_HOME /gradle/wrapper/gradle-wrapper.jar

# Determine el comando de Java que se utilizará para iniciar la JVM.
if [ -n  " $ JAVA_HOME " ] ;  luego
    if [ -x  " $ JAVA_HOME / jre / sh / java " ] ;  luego
        # El JDK de IBM en AIX utiliza ubicaciones extrañas para los ejecutables
        JAVACMD = " $ JAVA_HOME / jre / sh / java "
    más
        JAVACMD = " $ JAVA_HOME / bin / java "
    fi
    si [ !  -x  " $ JAVACMD " ] ;  luego
        die " ERROR: JAVA_HOME está configurado en un directorio no válido: $ JAVA_HOME
Configure la variable JAVA_HOME en su entorno para que coincida con
ubicación de su instalación de Java. "
    fi
más
    JAVACMD = " java "
    cuál java > / dev / null 2> & 1  || die " ERROR: JAVA_HOME no está configurado y no se pudo encontrar ningún comando 'java' en su RUTA.
Configure la variable JAVA_HOME en su entorno para que coincida con
ubicación de su instalación de Java. "
fi

# Incrementar el máximo de descriptores de archivos si podemos.
if [ " $ cygwin "  =  " false "  -a  " $ darwin "  =  " false "  -a  " $ nonstop "  =  " false " ] ;  luego
    MAX_FD_LIMIT = ` ulimit -H -n `
    si [ $?  -eq 0] ;  luego
        si [ " $ MAX_FD "  =  " máximo "  -o  " $ MAX_FD "  =  " máximo " ] ;  luego
            MAX_FD = " $ MAX_FD_LIMIT "
        fi
        ulimit -n $ MAX_FD
        si [ $?  -no 0] ;  luego
            advertir " No se pudo establecer el límite máximo de descriptor de archivo: $ MAX_FD "
        fi
    más
        advertir " No se pudo consultar el límite máximo de descriptores de archivos: $ MAX_FD_LIMIT "
    fi
fi

# Para Darwin, agregue opciones para especificar cómo aparece la aplicación en el dock
si  $ darwin ;  luego
    GRADLE_OPTS = " $ GRADLE_OPTS  \" -Xdock: nombre = $ APP_NAME \ "  \" -Xdock: icon = $ APP_HOME /media/gradle.icns \ " "
fi

# Para Cygwin, cambie las rutas al formato de Windows antes de ejecutar java
si  $ cygwin  ;  luego
    APP_HOME = ` cygpath --path --mixed " $ APP_HOME " `
    CLASSPATH = ` cygpath --path --mixed " $ CLASSPATH " `
    JAVACMD = ` cygpath --unix " $ JAVACMD " `

    # Construimos el patrón para que los argumentos se conviertan a través de cygpath
    ROOTDIRSRAW = ` encontrar -L / -maxdepth 1 -mindepth 1 de tipo d 2> / dev / null `
    SEP = " "
    para  dir  en  $ ROOTDIRSRAW  ;  hacer
        ROOTDIRS = " $ ROOTDIRS $ SEP $ dir "
        SEP = " | "
    hecho
    OURCYGPATTERN = " (^ ( $ ROOTDIRS )) "
    # Agregue un patrón definido por el usuario a los argumentos cygpath
    si [ " $ GRADLE_CYGPATTERN "  ! =  " " ] ;  luego
        OURCYGPATTERN = " $ OURCYGPATTERN | ( $ GRADLE_CYGPATTERN ) "
    fi
    # Ahora convierta los argumentos - kludge para limitarnos a / bin / sh
    i = 0
    para  arg  en  " $ @ "  ;  hacer
        COMPROBAR = ` echo " $ arg " | egrep -c " $ OURCYGPATTERN " - `
        CHECK2 = ` echo " $ arg " | egrep -c " ^ - " `                                  # ## Determinar si una opción

        si [ $ CHECK  -ne 0] && [ $ CHECK2  -eq 0] ;  luego                     # ## Agregó una condición
            eval  ` eco args $ i ` = ` cygpath --path --ignore --mixed " $ arg " `
        más
            eval  ` eco args $ i ` = " \" $ arg \" "
        fi
        i = $ (( i + 1 ))
    hecho
    caso  $ i  en
        (0) conjunto - ;;
        (1) set - " $ args0 " ;;
        (2) set - " $ args0 "  " $ args1 " ;;
        (3) set - " $ args0 "  " $ args1 "  " $ args2 " ;;
        (4) set - " $ args0 "  " $ args1 "  " $ args2 "  " $ args3 " ;;
        (5) set - " $ args0 "  " $ args1 "  " $ args2 "  " $ args3 "  " $ args4 " ;;
        (6) set - " $ args0 "  " $ args1 "  " $ args2 "  " $ args3 "  " $ args4 "  " $ args5 " ;;
        (7) set - " $ args0 "  " $ args1 "  " $ args2 "  " $ args3 "  " $ args4 "  " $ args5 "  " $ args6 " ;;
        (8) set - " $ args0 "  " $ args1 "  " $ args2 "  " $ args3 "  " $ args4 "  " $ args5 "  " $ args6 "  " $ args7 " ;;
        (9) set - " $ args0 "  " $ args1 "  " $ args2 "  " $ args3 "  " $ args4 "  " $ args5 "  " $ args6 "  " $ args7 "  " $ args8 " ;;
    esac
fi

# Escape de los argumentos de la aplicación
guardar () {
    para i no  printf % s \\ n " $ i "  | sed " s / '/' \\\\ '' / g; 1s / ^ / '/; \ $ s / \ $ /' \\\\ / "  ;  hecho
    echo  "  "
}
APP_ARGS = $ ( guardar " $ @ " )

# Recopile todos los argumentos para el comando java, siguiendo las reglas de sustitución y citas de shell
 conjunto de evaluación - $ DEFAULT_JVM_OPTS  $ JAVA_OPTS  $ GRADLE_OPTS  " \" -Dorg.gradle.appname = $ APP_BASE_NAME \ " " -classpath " \" $ CLASSPATH \ " " org.gradle.wrapper.GradleWrapperMain " $ APP_ARGS "

# por defecto deberíamos estar en el directorio del proyecto correcto, pero cuando se ejecuta desde Finder en Mac, el cwd es incorrecto
if [ " $ ( uname ) "  =  " Darwin " ] && [ " $ HOME "  =  " $ PWD " ] ;  luego
  cd  " $ ( dirname " $ 0 " ) "
fi

ejecutivo  " $ JAVACMD "  " $ @ "
 84  gradlew.bat 
@@ -0,0 +1,84 @@
@ if " % DEBUG% "  ==  " "  @ echo  desactivado
@ rem ############################################## #########################
@ rem
@ rem   script de inicio de Gradle para Windows
@ rem
@ rem ############################################## #########################

@ rem Establece el alcance local para las variables con el shell de Windows NT
si  " % OS% " == " Windows_NT "  setlocal

establecer  DIRNAME = % ~ dp0
si  " % DIRNAME% "  ==  " "  establezca  DIRNAME = .
establecer  APP_BASE_NAME = % ~ n0
establecer  APP_HOME = % DIRNAME%

@ rem Agregue aquí las opciones predeterminadas de JVM. También puede utilizar JAVA_OPTS y GRADLE_OPTS para pasar las opciones de JVM a este script.
establecer  DEFAULT_JVM_OPTS =

@ rem Encuentra java.exe
si está  definido JAVA_HOME goto findJavaFromJavaHome

establecer  JAVA_EXE = java.exe
% JAVA_EXE% -version > NUL  2 > & 1
si  " % ERRORLEVEL% "  ==  " 0 "  goto init

eco .
echo ERROR: JAVA_HOME no está configurado y no se pudo encontrar ningún comando 'java' en su RUTA.
eco .
echo Configure la variable JAVA_HOME en su entorno para que coincida con
eco de la ubicación de su instalación de Java.

Ir a fallar

: findJavaFromJavaHome
establecer  JAVA_HOME = % JAVA_HOME: " =%
establecer  JAVA_EXE = % JAVA_HOME% /bin/java.exe

si  existe  " % JAVA_EXE% "  goto init

eco .
echo ERROR: JAVA_HOME está configurado en un directorio no válido: % JAVA_HOME%
eco .
echo Configure la variable JAVA_HOME en su entorno para que coincida con
eco de la ubicación de su instalación de Java.

Ir a fallar

: init
@ rem Obtiene argumentos de la línea de comandos, manejando variantes de Windows

si  no  " % OS% "  ==  " Windows_NT "  Goto win9xME_args

: win9xME_args
@ rem Slurp los argumentos de la línea de comandos.
establecer  CMD_LINE_ARGS =
establecer  _SKIP = 2

: win9xME_args_slurp
si  " x% ~ 1 "  ==  " x "  ir a ejecutar

establecer  CMD_LINE_ARGS = % *

: ejecutar
@ rem Configura la línea de comando

establecer  CLASSPATH = % APP_HOME% \ gradle \ wrapper \ gradle-wrapper.jar

@ rem Ejecutar Gradle
" % JAVA_EXE% "  % DEFAULT_JVM_OPTS  %% JAVA_OPTS%%  GRADLE_OPTS%  " -Dorg.gradle.appname = % APP_BASE_NAME% " -classpath " % CLASSPATH% " org.gradle.wrapper.GradleWrapperMain % CMD_LINE_ARGS%

: fin
@ rem Finaliza el ámbito local para las variables con el shell de Windows NT
si  " % ERRORLEVEL% " == " 0 "  ir a mainEnd

: fallar
rem Establezca la variable GRADLE_EXIT_CONSOLE si necesita el código de retorno _script_ en lugar de
rem el código de retorno _cmd.exe / c_!
si   no  " "  ==  " % GRADLE_EXIT_CONSOLE% "  salida  1
salir / b 1

: mainEnd
si  " % OS% " == " Windows_NT "  endlocal

: omega
 2  settings.gradle 
@@ -0,0 +1,2 @@
incluir ' : aplicación '
rootProject . name =  " Petagram " 
