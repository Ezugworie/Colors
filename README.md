## Material Color Code Android

  
// Black based on same hue as $gray-900
$black: #1b1f23 !default;
$white: #fff !default;

//
//
// -------- Grays --------
$gray-000:        #fafbfc !default;
$gray-100:        #f6f8fa !default;
$gray-200:        #e1e4e8 !default;
$gray-300:        #d1d5da !default;
$gray-400:        #959da5 !default;
$gray-500:        #6a737d !default;
$gray-600:        #586069 !default;
$gray-700:        #444d56 !default;
$gray-800:        #2f363d !default;
$gray-900:        #24292e !default; // body font color

// -------- Blue --------
$blue-000:        #f1f8ff !default;
$blue-100:        #dbedff !default;
$blue-200:        #c8e1ff !default;
$blue-300:        #79b8ff !default;
$blue-400:        #2188ff !default;
$blue-500:        #0366d6 !default; // Default: Passes AA with #fff
$blue-600:        #005cc5 !default;
$blue-700:        #044289 !default;
$blue-800:        #032f62 !default;
$blue-900:        #05264c !default; // Passes with 1/2/300 blues

// -------- Green --------
$green-000:       #f0fff4 !default;
$green-100:       #dcffe4 !default;
$green-200:       #bef5cb !default;
$green-300:       #85e89d !default;
$green-400:       #34d058 !default;
$green-500:       #28a745 !default; // Default. passes AA Large
$green-600:       #22863a !default; // Text green, passes AA on #fff
$green-700:       #176f2c !default;
$green-800:       #165c26 !default;
$green-900:       #144620 !default;

// -------- Yellow --------
$yellow-000:      #fffdef !default;
$yellow-100:      #fffbdd !default;
$yellow-200:      #fff5b1 !default;
$yellow-300:      #ffea7f !default;
$yellow-400:      #ffdf5d !default;
$yellow-500:      #ffd33d !default;
$yellow-600:      #f9c513 !default;
$yellow-700:      #dbab09 !default;
$yellow-800:      #b08800 !default;
$yellow-900:      #735c0f !default;

// -------- Orange --------
$orange-000:      #fff8f2 !default;
$orange-100:      #ffebda !default;
$orange-200:      #ffd1ac !default;
$orange-300:      #ffab70 !default;
$orange-400:      #fb8532 !default;
$orange-500:      #f66a0a !default; // Default. passes AA Large with #fff
$orange-600:      #e36209 !default;
$orange-700:      #d15704 !default;
$orange-800:      #c24e00 !default;
$orange-900:      #a04100 !default;

// -------- Red --------
$red-000:         #ffeef0 !default;
$red-100:         #ffdce0 !default;
$red-200:         #fdaeb7 !default;
$red-300:         #f97583 !default;
$red-400:         #ea4a5a !default;
$red-500:         #d73a49 !default; // Default. passes AA
$red-600:         #cb2431 !default;
$red-700:         #b31d28 !default;
$red-800:         #9e1c23 !default;
$red-900:         #86181d !default;

// -------- Purple --------
$purple-000:      #f5f0ff !default;
$purple-100:      #e6dcfd !default;
$purple-200:      #d1bcf9 !default;
$purple-300:      #b392f0 !default;
$purple-400:      #8a63d2 !default;
$purple-500:      #6f42c1 !default; // passes AA with #fff
$purple-600:      #5a32a3 !default;
$purple-700:      #4c2889 !default;
$purple-800:      #3a1d6e !default;
$purple-900:      #29134e !default;

// -------- Pink --------
$pink-000:      #ffeef8 !default;
$pink-100:      #fedbf0 !default;
$pink-200:      #f9b3dd !default;
$pink-300:      #f692ce !default;
$pink-400:      #ec6cb9 !default;
$pink-500:      #ea4aaa !default;
$pink-600:      #d03592 !default;
$pink-700:      #b93a86 !default;
$pink-800:      #99306f !default;
$pink-900:      #6d224f !default;

// -------- Fades --------
$black-fade-15:      rgba($black, 0.15) !default;
$black-fade-30:      rgba($black, 0.3) !default;
$black-fade-50:      rgba($black, 0.5) !default;
$black-fade-70:      rgba($black, 0.7) !default;
$black-fade-85:      rgba($black, 0.85) !default;

$white-fade-15:      rgba($white, 0.15) !default;
$white-fade-30:      rgba($white, 0.3) !default;
$white-fade-50:      rgba($white, 0.5) !default;
$white-fade-70:      rgba($white, 0.7) !default;
$white-fade-85:      rgba($white, 0.85) !default;

// -------- Color defaults --------
$red:         $red-500 !default;
$purple:      $purple-500 !default;
$blue:        $blue-500 !default;
$green:       $green-500 !default;
$yellow:      $yellow-500 !default;
$orange:      $orange-500 !default;

$gray-dark:   $gray-900 !default;
$gray-light:  $gray-400 !default;
$gray:        $gray-500 !default;

// -------- Color gradient maps --------

$grays: (
  0: $gray-000,
  1: $gray-100,
  2: $gray-200,
  3: $gray-300,
  4: $gray-400,
  5: $gray-500,
  6: $gray-600,
  7: $gray-700,
  8: $gray-800,
  9: $gray-900,
) !default;

$blues: (
  0: $blue-000,
  1: $blue-100,
  2: $blue-200,
  3: $blue-300,
  4: $blue-400,
  5: $blue-500,
  6: $blue-600,
  7: $blue-700,
  8: $blue-800,
  9: $blue-900,
) !default;

$greens: (
  0: $green-000,
  1: $green-100,
  2: $green-200,
  3: $green-300,
  4: $green-400,
  5: $green-500,
  6: $green-600,
  7: $green-700,
  8: $green-800,
  9: $green-900,
) !default;

$yellows: (
  0: $yellow-000,
  1: $yellow-100,
  2: $yellow-200,
  3: $yellow-300,
  4: $yellow-400,
  5: $yellow-500,
  6: $yellow-600,
  7: $yellow-700,
  8: $yellow-800,
  9: $yellow-900,
) !default;

$oranges: (
  0: $orange-000,
  1: $orange-100,
  2: $orange-200,
  3: $orange-300,
  4: $orange-400,
  5: $orange-500,
  6: $orange-600,
  7: $orange-700,
  8: $orange-800,
  9: $orange-900,
) !default;

$reds: (
  0: $red-000,
  1: $red-100,
  2: $red-200,
  3: $red-300,
  4: $red-400,
  5: $red-500,
  6: $red-600,
  7: $red-700,
  8: $red-800,
  9: $red-900,
) !default;

$purples: (
  0: $purple-000,
  1: $purple-100,
  2: $purple-200,
  3: $purple-300,
  4: $purple-400,
  5: $purple-500,
  6: $purple-600,
  7: $purple-700,
  8: $purple-800,
  9: $purple-900,
) !default;

$pinks: (
  0: $pink-000,
  1: $pink-100,
  2: $pink-200,
  3: $pink-300,
  4: $pink-400,
  5: $pink-500,
  6: $pink-600,
  7: $pink-700,
  8: $pink-800,
  9: $pink-900,
) !default;

$hue-maps: (
  "gray": $grays,
  "blue": $blues,
  "green": $greens,
  "yellow": $yellows,
  "orange": $oranges,
  "red": $reds,
  "purple": $purples,
  "pink": $pinks,
) !default;

    <color name="red_50">#FFEBEE</color>
    <color name="red_100">#FFCDD2</color>
    <color name="red_200">#EF9A9A</color>
    <color name="red_300">#E57373</color>
    <color name="red_400">#EF5350</color>
    <color name="red_500">#F44336</color>
    <color name="red_600">#E53935</color>
    <color name="red_700">#D32F2F</color>
    <color name="red_800">#C62828</color>
    <color name="red_900">#B71C1C</color>
    <color name="red_A100">#FF8A80</color>
    <color name="red_A200">#FF5252</color>
    <color name="red_A400">#FF1744</color>
    <color name="red_A700">#D50000</color>

    <color name="deep_purple_50">#EDE7F6</color>
    <color name="deep_purple_100">#D1C4E9</color>
    <color name="deep_purple_200">#B39DDB</color>
    <color name="deep_purple_300">#9575CD</color>
    <color name="deep_purple_400">#7E57C2</color>
    <color name="deep_purple_500">#673AB7</color>
    <color name="deep_purple_600">#5E35B1</color>
    <color name="deep_purple_700">#512DA8</color>
    <color name="deep_purple_800">#4527A0</color>
    <color name="deep_purple_900">#311B92</color>
    <color name="deep_purple_A100">#B388FF</color>
    <color name="deep_purple_A200">#7C4DFF</color>
    <color name="deep_purple_A400">#651FFF</color>
    <color name="deep_purple_A700">#6200EA</color>

    <color name="light_blue_50">#E1F5FE</color>
    <color name="light_blue_100">#B3E5FC</color>
    <color name="light_blue_200">#81D4FA</color>
    <color name="light_blue_300">#4FC3F7</color>
    <color name="light_blue_400">#29B6F6</color>
    <color name="light_blue_500">#03A9F4</color>
    <color name="light_blue_600">#039BE5</color>
    <color name="light_blue_700">#0288D1</color>
    <color name="light_blue_800">#0277BD</color>
    <color name="light_blue_900">#01579B</color>
    <color name="light_blue_A100">#80D8FF</color>
    <color name="light_blue_A200">#40C4FF</color>
    <color name="light_blue_A400">#00B0FF</color>
    <color name="light_blue_A700">#0091EA</color>

    <color name="green_50">#E8F5E9</color>
    <color name="green_100">#C8E6C9</color>
    <color name="green_200">#A5D6A7</color>
    <color name="green_300">#81C784</color>
    <color name="green_400">#66BB6A</color>
    <color name="green_500">#4CAF50</color>
    <color name="green_600">#43A047</color>
    <color name="green_700">#388E3C</color>
    <color name="green_800">#2E7D32</color>
    <color name="green_900">#1B5E20</color>
    <color name="green_A100">#B9F6CA</color>
    <color name="green_A200">#69F0AE</color>
    <color name="green_A400">#00E676</color>
    <color name="green_A700">#00C853</color>

    <color name="yellow_50">#FFFDE7</color>
    <color name="yellow_100">#FFF9C4</color>
    <color name="yellow_200">#FFF59D</color>
    <color name="yellow_300">#FFF176</color>
    <color name="yellow_400">#FFEE58</color>
    <color name="yellow_500">#FFEB3B</color>
    <color name="yellow_600">#FDD835</color>
    <color name="yellow_700">#FBC02D</color>
    <color name="yellow_800">#F9A825</color>
    <color name="yellow_900">#F57F17</color>
    <color name="yellow_A100">#FFFF8D</color>
    <color name="yellow_A200">#FFFF00</color>
    <color name="yellow_A400">#FFEA00</color>
    <color name="yellow_A700">#FFD600</color>

    <color name="deep_orange_50">#FBE9E7</color>
    <color name="deep_orange_100">#FFCCBC</color>
    <color name="deep_orange_200">#FFAB91</color>
    <color name="deep_orange_300">#FF8A65</color>
    <color name="deep_orange_400">#FF7043</color>
    <color name="deep_orange_500">#FF5722</color>
    <color name="deep_orange_600">#F4511E</color>
    <color name="deep_orange_700">#E64A19</color>
    <color name="deep_orange_800">#D84315</color>
    <color name="deep_orange_900">#BF360C</color>
    <color name="deep_orange_A100">#FF9E80</color>
    <color name="deep_orange_A200">#FF6E40</color>
    <color name="deep_orange_A400">#FF3D00</color>
    <color name="deep_orange_A700">#DD2C00</color>

    <color name="blue_grey_50">#ECEFF1</color>
    <color name="blue_grey_100">#CFD8DC</color>
    <color name="blue_grey_200">#B0BEC5</color>
    <color name="blue_grey_300">#90A4AE</color>
    <color name="blue_grey_400">#78909C</color>
    <color name="blue_grey_500">#607D8B</color>
    <color name="blue_grey_600">#546E7A</color>
    <color name="blue_grey_700">#455A64</color>
    <color name="blue_grey_800">#37474F</color>
    <color name="blue_grey_900">#263238</color>

    <color name="pink_50">#FCE4EC</color>
    <color name="pink_100">#F8BBD0</color>
    <color name="pink_200">#F48FB1</color>
    <color name="pink_300">#F06292</color>
    <color name="pink_400">#EC407A</color>
    <color name="pink_500">#E91E63</color>
    <color name="pink_600">#D81B60</color>
    <color name="pink_700">#C2185B</color>
    <color name="pink_800">#AD1457</color>
    <color name="pink_900">#880E4F</color>
    <color name="pink_A100">#FF80AB</color>
    <color name="pink_A200">#FF4081</color>
    <color name="pink_A400">#F50057</color>
    <color name="pink_A700">#C51162</color>

    <color name="indigo_50">#E8EAF6</color>
    <color name="indigo_100">#C5CAE9</color>
    <color name="indigo_200">#9FA8DA</color>
    <color name="indigo_300">#7986CB</color>
    <color name="indigo_400">#5C6BC0</color>
    <color name="indigo_500">#3F51B5</color>
    <color name="indigo_600">#3949AB</color>
    <color name="indigo_700">#303F9F</color>
    <color name="indigo_800">#283593</color>
    <color name="indigo_900">#1A237E</color>
    <color name="indigo_A100">#8C9EFF</color>
    <color name="indigo_A200">#536DFE</color>
    <color name="indigo_A400">#3D5AFE</color>
    <color name="indigo_A700">#304FFE</color>

    <color name="cyan_50">#E0F7FA</color>
    <color name="cyan_100">#B2EBF2</color>
    <color name="cyan_200">#80DEEA</color>
    <color name="cyan_300">#4DD0E1</color>
    <color name="cyan_400">#26C6DA</color>
    <color name="cyan_500">#00BCD4</color>
    <color name="cyan_600">#00ACC1</color>
    <color name="cyan_700">#0097A7</color>
    <color name="cyan_800">#00838F</color>
    <color name="cyan_900">#006064</color>
    <color name="cyan_A100">#84FFFF</color>
    <color name="cyan_A200">#18FFFF</color>
    <color name="cyan_A400">#00E5FF</color>
    <color name="cyan_A700">#00B8D4</color>

    <color name="light_green_50">#F1F8E9</color>
    <color name="light_green_100">#DCEDC8</color>
    <color name="light_green_200">#C5E1A5</color>
    <color name="light_green_300">#AED581</color>
    <color name="light_green_400">#9CCC65</color>
    <color name="light_green_500">#8BC34A</color>
    <color name="light_green_600">#7CB342</color>
    <color name="light_green_700">#689F38</color>
    <color name="light_green_800">#558B2F</color>
    <color name="light_green_900">#33691E</color>
    <color name="light_green_A100">#CCFF90</color>
    <color name="light_green_A200">#B2FF59</color>
    <color name="light_green_A400">#76FF03</color>
    <color name="light_green_A700">#64DD17</color>

    <color name="amber_50">#FFF8E1</color>
    <color name="amber_100">#FFECB3</color>
    <color name="amber_200">#FFE082</color>
    <color name="amber_300">#FFD54F</color>
    <color name="amber_400">#FFCA28</color>
    <color name="amber_500">#FFC107</color>
    <color name="amber_600">#FFB300</color>
    <color name="amber_700">#FFA000</color>
    <color name="amber_800">#FF8F00</color>
    <color name="amber_900">#FF6F00</color>
    <color name="amber_A100">#FFE57F</color>
    <color name="amber_A200">#FFD740</color>
    <color name="amber_A400">#FFC400</color>
    <color name="amber_A700">#FFAB00</color>

    <color name="brown_50">#EFEBE9</color>
    <color name="brown_100">#D7CCC8</color>
    <color name="brown_200">#BCAAA4</color>
    <color name="brown_300">#A1887F</color>
    <color name="brown_400">#8D6E63</color>
    <color name="brown_500">#795548</color>
    <color name="brown_600">#6D4C41</color>
    <color name="brown_700">#5D4037</color>
    <color name="brown_800">#4E342E</color>
    <color name="brown_900">#3E2723</color>

    <color name="purple_50">#F3E5F5</color>
    <color name="purple_100">#E1BEE7</color>
    <color name="purple_200">#CE93D8</color>
    <color name="purple_300">#BA68C8</color>
    <color name="purple_400">#AB47BC</color>
    <color name="purple_500">#9C27B0</color>
    <color name="purple_600">#8E24AA</color>
    <color name="purple_700">#7B1FA2</color>
    <color name="purple_800">#6A1B9A</color>
    <color name="purple_900">#4A148C</color>
    <color name="purple_A100">#EA80FC</color>
    <color name="purple_A200">#E040FB</color>
    <color name="purple_A400">#D500F9</color>
    <color name="purple_A700">#AA00FF</color>

    <color name="blue_50">#E3F2FD</color>
    <color name="blue_100">#BBDEFB</color>
    <color name="blue_200">#90CAF9</color>
    <color name="blue_300">#64B5F6</color>
    <color name="blue_400">#42A5F5</color>
    <color name="blue_500">#2196F3</color>
    <color name="blue_600">#1E88E5</color>
    <color name="blue_700">#1976D2</color>
    <color name="blue_800">#1565C0</color>
    <color name="blue_900">#0D47A1</color>
    <color name="blue_A100">#82B1FF</color>
    <color name="blue_A200">#448AFF</color>
    <color name="blue_A400">#2979FF</color>
    <color name="blue_A700">#2962FF</color>

    <color name="teal_50">#E0F2F1</color>
    <color name="teal_100">#B2DFDB</color>
    <color name="teal_200">#80CBC4</color>
    <color name="teal_300">#4DB6AC</color>
    <color name="teal_400">#26A69A</color>
    <color name="teal_500">#009688</color>
    <color name="teal_600">#00897B</color>
    <color name="teal_700">#00796B</color>
    <color name="teal_800">#00695C</color>
    <color name="teal_900">#004D40</color>
    <color name="teal_A100">#A7FFEB</color>
    <color name="teal_A200">#64FFDA</color>
    <color name="teal_A400">#1DE9B6</color>
    <color name="teal_A700">#00BFA5</color>

    <color name="lime_50">#F9FBE7</color>
    <color name="lime_100">#F0F4C3</color>
    <color name="lime_200">#E6EE9C</color>
    <color name="lime_300">#DCE775</color>
    <color name="lime_400">#D4E157</color>
    <color name="lime_500">#CDDC39</color>
    <color name="lime_600">#C0CA33</color>
    <color name="lime_700">#AFB42B</color>
    <color name="lime_800">#9E9D24</color>
    <color name="lime_900">#827717</color>
    <color name="lime_A100">#F4FF81</color>
    <color name="lime_A200">#EEFF41</color>
    <color name="lime_A400">#C6FF00</color>
    <color name="lime_A700">#AEEA00</color>

    <color name="orange_50">#FFF3E0</color>
    <color name="orange_100">#FFE0B2</color>
    <color name="orange_200">#FFCC80</color>
    <color name="orange_300">#FFB74D</color>
    <color name="orange_400">#FFA726</color>
    <color name="orange_500">#FF9800</color>
    <color name="orange_600">#FB8C00</color>
    <color name="orange_700">#F57C00</color>
    <color name="orange_800">#EF6C00</color>
    <color name="orange_900">#E65100</color>
    <color name="orange_A100">#FFD180</color>
    <color name="orange_A200">#FFAB40</color>
    <color name="orange_A400">#FF9100</color>
    <color name="orange_A700">#FF6D00</color>

    <color name="grey_50">#FAFAFA</color>
    <color name="grey_100">#F5F5F5</color>
    <color name="grey_200">#EEEEEE</color>
    <color name="grey_300">#E0E0E0</color>
    <color name="grey_400">#BDBDBD</color>
    <color name="grey_500">#9E9E9E</color>
    <color name="grey_600">#757575</color>
    <color name="grey_700">#616161</color>
    <color name="grey_800">#424242</color>
    <color name="grey_900">#212121</color>

    <color name="black">#000000</color>
    <color name="white">#FFFFFF</color>

    <!-- Colors for the app -->
    <color name="primary">@color/indigo_500</color>
    <color name="primary_dark">@color/indigo_700</color>
    <color name="accent">@color/pink_A200</color>
    
    <!--Light Background Dark Text-->
    <color name="light_bg_dark_primary_text">#DE000000</color>
    <color name="light_bg_dark_secondary_text">#8A000000</color>
    <color name="light_bg_dark_disabled_text">#61000000</color>
    <color name="light_bg_dark_hint_text">#61000000</color>

    <!--Dark Background Light Text-->
    <color name="dark_bg_light_primary_text">#FFFFFFFF</color>
    <color name="dark_bg_light_secondary_text">#B3FFFFFF</color>
    <color name="dark_bg_light_disabled_text">#80FFFFFF</color>
    <color name="dark_bg_light_hint_text">#80FFFFFF</color>
