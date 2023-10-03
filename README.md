# Translatorapp
Simple Translator App

## Functionality

### Layout
- The app's layout follows the design requirements:
   

### Operations
Users can select over 30 languages to translate from and to. 


### Input Handling
- Users can enter phrases by typing
- Users selct the translate button to translate
- The app displays the current input and operator in the top TextView.



The following **extensions** are implemented:
import android.app.ProgressDialog
import androidx.appcompat.app.AppCompatActivity
import android.os.Bundle
import android.util.Log
import android.view.Menu
import android.widget.EditText
import android.widget.PopupMenu
import android.widget.TextView
import android.widget.Toast
import com.google.android.material.button.MaterialButton
import com.google.mlkit.common.model.DownloadConditions
import com.google.mlkit.nl.translate.TranslateLanguage
import com.google.mlkit.nl.translate.Translation
import com.google.mlkit.nl.translate.Translator
import com.google.mlkit.nl.translate.TranslatorOptions
import java.util.Locale


## Video Walkthrough

Here's a walkthrough of implemented user stories:



<video src="Translatorapp%20%E2%80%93%20MainActivity.kt%20%5BTranslatorapp.app.main%5D%202023-10-03%2012-07-12.mp4" controls title="Title"></video>

![Alt text](TranslatorApp.gif)


## License

    Copyright [2023] [Kisheeth Reddivari]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
