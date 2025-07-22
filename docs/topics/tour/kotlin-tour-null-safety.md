package com.poplo.app

import android.os.Bundle
import androidx.activity.ComponentActivity
import androidx.activity.compose.setContent
import com.poplo.app.ui.screens.HomeScreen
import com.poplo.app.ui.theme.PoploTheme

class MainActivity : ComponentActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContent {
            PoploTheme {
                HomeScreen()
            }
        }
    }
}
