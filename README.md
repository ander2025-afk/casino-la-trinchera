# casino-la-trinchera
App tragamonedas - Casino La Trinchera
## 📄 Documento del Proyecto

Puedes consultar los objetivos generales y específicos del proyecto en el siguiente archivo:

👉 [Ver Objetivos del Casino La Trinchera](Objetivo_Casino_La_Trinchera.pdf)
# 🎰 Casino La Trinchera

Bienvenido al proyecto de la app tipo tragamonedas **Casino La Trinchera**.

## 📱 Descripción
Una app de juego divertida y visualmente atractiva que permite girar, ganar monedas virtuales y pasar un buen rato.  
Ideal para dispositivos Android, lista para ser instalada, subida a GitHub y publicada en Google Play Store.

## 🧾 Características
- Tragamonedas con botón de giro funcional  
- Animaciones y sonidos tipo casino  
- Recompensas con monedas virtuales  
- Nombre comercial: *Casino La Trinchera*  
- Frase: *Gira, gana y diviértete*  
- Preparada para compras dentro de la app (opcional)

## 🧠 Objetivos del Proyecto

Consulta los objetivos generales y específicos en el siguiente documento:

👉 [Ver Objetivos del Casino La Trinchera](Objetivo_Casino_La_Trinchera.pdf)

---

## 🔧 Tecnologías
- Android Studio / Java  
- XML para diseño visual  
- Compatible con formato APK o AAB

## 👤 Autor
**Anderson Stiven Rojas Manrique**  
Usuario GitHub: `ander2025-afk`  
Correo: esteven201825@gmail.com
MainActivity.java
package com.example.casinolatrinchera;

import android.os.Bundle;
import android.widget.Button;
import android.widget.ImageView;
import android.widget.TextView;
import androidx.appcompat.app.AppCompatActivity;
import java.util.Random;

public class MainActivity extends AppCompatActivity {
    private ImageView slot1, slot2, slot3;
    private TextView result, coins;
    private int coinCount = 100;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        // Aquí va el resto del código...
    }
}
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.example.casinolatrinchera">

    <application
        android:label="Casino La Trinchera"
        android:theme="@style/Theme.AppCompat.Light.DarkActionBar">
        <activity android:name=".MainActivity">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />
                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>
</manifest>
