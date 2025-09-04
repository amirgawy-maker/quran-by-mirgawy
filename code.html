<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quran by Bishr</title>
    <link href="https://fonts.googleapis.com/css2?family=Amiri&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Amiri', serif;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
            direction: rtl;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            padding: 20px 0;
        }

        header h1 {
            font-size: 2.5rem;
            color: #2c3e50;
        }

        header p {
            font-size: 1.2rem;
            color: #7f8c8d;
        }

        .surah-selector {
            margin: 20px 0;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 15px;
        }

        .surah-selector select {
            padding: 10px;
            font-size: 1.2rem;
            border: 1px solid #ccc;
            border-radius: 5px;
            width: 100%;
            max-width: 300px;
            background-color: #fff;
            cursor: pointer;
            transition: border-color 0.3s ease;
        }

        .surah-selector select:focus {
            border-color: #27ae60;
            outline: none;
        }

        .play-surah-button {
            padding: 12px 24px;
            font-size: 1.2rem;
            font-weight: 500;
            background: linear-gradient(135deg, #27ae60, #2ecc71);
            color: white;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            display: none;
            transition: all 0.3s ease;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        .play-surah-button:hover {
            background: linear-gradient(135deg, #219a52, #27ae60);
            transform: translateY(-2px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3);
        }

        .play-surah-button:active {
            transform: translateY(0);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        .play-surah-button.pause {
            background: linear-gradient(135deg, #e74c3c, #c0392b);
        }

        .play-surah-button.pause:hover {
            background: linear-gradient(135deg, #c0392b, #e74c3c);
        }

        .verses-container {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }

        .verse {
            font-size: 1.5rem;
            padding: 10px;
            border-bottom: 1px solid #eee;
            line-height: 2;
            transition: background-color 0.3s ease;
        }

        .verse:last-child {
            border-bottom: none;
        }

        .verse.active {
            background-color: #e8f5e9;
            border-radius: 5px;
        }

        .loading, .error, .buffering {
            text-align: center;
            padding: 20px;
            color: #7f8c8d;
        }

        .error {
            color: #e74c3c;
        }

        .buffering {
            color: #3498db;
            font-size: 1.1rem;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }

            .surah-selector select, .play-surah-button {
                font-size: 1rem;
            }

            .verse {
                font-size: 1.3rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>القرآن الكريم</h1>
            <p>قراءة سلسة وسهلة لكتاب الله</p>
	      <p>تصميم احمد المرجاوي ارجو منكم الدعاء</p>

        </header>
        <div class="surah-selector">
            <select id="surahSelect" onchange="loadSurah()">
                <option value="">اختر سورة</option>
            </select>
            <select id="reciterSelect" onchange="loadSurah()">
                <option value="ar.alafasy">مشاري العفاسي</option>
                <option value="ar.mahermuaiqly">ماهر المعيقلي</option>
                <option value="ar.husary">محمود خليل الحصري</option>
                <option value="ar.abdulsamad">عبد الباسط عبد الصمد</option>
                <option value="banna_complete">محمود علي البنا (سورة كاملة)</option>
                <option value="mustafa_complete">مصطفى إسماعيل (سورة كاملة)</option>
                <option value="ar.abdulbasitmurattal">عبد الباسط عبد الصمد (مرتل)</option>
                <option value="ar.abdullahbasfar">عبد الله بصفر</option>
                <option value="ar.abdurrahmaansudais">عبدالرحمن السديس</option>
                <option value="ar.shaatree">أبو بكر الشاطري</option>
                <option value="ar.ahmedajamy">أحمد بن علي العجمي</option>
                <option value="ar.hanirifai">هاني الرفاعي</option>
                <option value="ar.husarymujawwad">محمود خليل الحصري (مجود)</option>
                <option value="ar.hudhaify">علي بن عبدالرحمن الحذيفي</option>
                <option value="ar.ibrahimakhbar">إبراهيم الأخضر</option>
                <option value="ar.minshawi">محمد صديق المنشاوي</option>
                <option value="ar.minshawimujawwad">محمد صديق المنشاوي (مجود)</option>
                <option value="ar.muhammadayyoub">محمد أيوب</option>
                <option value="ar.muhammadjibreel">محمد جبريل</option>
                <option value="ar.saoodshuraym">سعود الشريم</option>
            </select>
            <button id="playSurahButton" class="play-surah-button" onclick="togglePlaySurah()">تشغيل السورة</button>
        </div>
        <div id="verses" class="verses-container"></div>
    </div>
    <script>
        let currentAudio = null;
        let isPlayingSurah = false;
        let currentAyahIndex = 0;
        let ayahs = [];
        let completeSurah = false;
        let completeAudioUrl = '';

        // تحميل قائمة السور عند تحميل الصفحة
        document.addEventListener('DOMContentLoaded', () => {
            loadSurahList();
        });

        // تحميل قائمة السور من API
        async function loadSurahList() {
            const surahSelect = document.getElementById('surahSelect');
            surahSelect.disabled = true;
            try {
                const response = await fetch('https://api.alquran.cloud/v1/quran/ar');
                if (!response.ok) throw new Error('فشل جلب قائمة السور');
                const quranData = await response.json();

                quranData.data.surahs.forEach(surah => {
                    const option = document.createElement('option');
                    option.value = surah.number;
                    option.textContent = `${surah.number}. ${surah.name}`;
                    surahSelect.appendChild(option);
                });
                surahSelect.disabled = false;
            } catch (error) {
                console.error('خطأ في تحميل قائمة السور:', error);
                surahSelect.disabled = false;
                document.getElementById('verses').innerHTML = '<p class="error">حدث خطأ أثناء تحميل قائمة السور. تأكد من اتصالك بالإنترنت وحاول مرة أخرى.</p>';
            }
        }

        // تحميل الآيات عند اختيار سورة أو قارئ
        async function loadSurah() {
            const surahSelect = document.getElementById('surahSelect');
            const reciterSelect = document.getElementById('reciterSelect');
            const surahNumber = surahSelect.value;
            const reciter = reciterSelect.value;
            const versesContainer = document.getElementById('verses');
            const playSurahButton = document.getElementById('playSurahButton');

            if (!surahNumber) {
                versesContainer.innerHTML = '';
                playSurahButton.style.display = 'none';
                stopSurah();
                return;
            }

            versesContainer.innerHTML = '<div class="loading">جاري تحميل الآيات...</div>';
            completeSurah = false;
            completeAudioUrl = '';
            ayahs = [];

            try {
                // جلب بيانات السورة النصية
                const textResponse = await fetch(`https://api.alquran.cloud/v1/surah/${surahNumber}/ar`);
                if (!textResponse.ok) throw new Error('فشل جلب نصوص الآيات');
                const textData = await textResponse.json();
                ayahs = textData.data.ayahs;

                if (reciter === 'banna_complete' || reciter === 'mustafa_complete') {
                    completeSurah = true;
                    const paddedSurah = surahNumber.padStart(3, '0');
                    if (reciter === 'banna_complete') {
                        completeAudioUrl = `https://server8.mp3quran.net/bna/${paddedSurah}.mp3`;
                    } else if (reciter === 'mustafa_complete') {
                        completeAudioUrl = `https://server8.mp3quran.net/mustafa/${paddedSurah}.mp3`;
                    }
                } else {
                    // جلب بيانات الصوت للقارئ المختار من alquran.cloud
                    const audioResponse = await fetch(`https://api.alquran.cloud/v1/surah/${surahNumber}/${reciter}`);
                    if (!audioResponse.ok) throw new Error('فشل جلب الصوت. جرب قارئًا آخر.');
                    const audioData = await audioResponse.json();
                    const audioAyahs = audioData.data.ayahs;

                    ayahs.forEach((ayah, index) => {
                        ayah.audio = audioAyahs[index].audio;
                    });
                }

                versesContainer.innerHTML = '';
                ayahs.forEach((ayah, index) => {
                    const verseElement = document.createElement('div');
                    verseElement.classList.add('verse');
                    verseElement.dataset.index = index;
                    if (!completeSurah) {
                        verseElement.dataset.audio = ayah.audio;
                    }
                    verseElement.innerHTML = `<span>${ayah.text} (${ayah.numberInSurah})</span>`;
                    versesContainer.appendChild(verseElement);
                });

                playSurahButton.style.display = 'inline-block';
            } catch (error) {
                console.error('خطأ في تحميل الآيات أو الصوت:', error);
                versesContainer.innerHTML = '<p class="error">حدث خطأ أثناء تحميل الآيات أو الصوت. تأكد من اتصالك بالإنترنت وحاول مرة أخرى.</p>';
                playSurahButton.style.display = 'none';
            }
        }

        // تشغيل/إيقاف السورة
        function togglePlaySurah() {
            if (isPlayingSurah) {
                stopSurah();
            } else {
                playSurah();
            }
        }

        // تشغيل السورة
        async function playSurah() {
            const playSurahButton = document.getElementById('playSurahButton');
            if (currentAyahIndex >= ayahs.length) {
                currentAyahIndex = 0;
            }

            document.querySelectorAll('.verse').forEach(verse => {
                verse.classList.remove('active');
            });

            if (currentAudio) {
                currentAudio.pause();
                currentAudio = null;
            }

            if (completeSurah) {
                // تشغيل السورة الكاملة
                currentAudio = new Audio(completeAudioUrl);
                currentAudio.preload = 'auto';
                try {
                    await currentAudio.play();
                    isPlayingSurah = true;
                    playSurahButton.textContent = 'إيقاف مؤقت';
                    playSurahButton.classList.add('pause');
                    // لا تمييز للآيات لأنها سورة كاملة
                    currentAudio.onended = () => {
                        stopSurah();
                    };
                } catch (error) {
                    console.error('خطأ في تشغيل الصوت:', error);
                    document.getElementById('verses').innerHTML = '<p class="error">فشل تشغيل الصوت. تأكد من إعدادات المتصفح وجرب مرة أخرى.</p>';
                    stopSurah();
                }
            } else {
                // تشغيل آية بآية
                const verseElement = document.querySelectorAll('.verse')[currentAyahIndex];
                const audioUrl = verseElement.dataset.audio;

                if (!audioUrl) {
                    console.error('رابط الصوت غير متوفر');
                    stopSurah();
                    return;
                }

                currentAudio = new Audio(audioUrl);
                currentAudio.preload = 'auto';
                try {
                    await currentAudio.play();
                    isPlayingSurah = true;
                    playSurahButton.textContent = 'إيقاف مؤقت';
                    playSurahButton.classList.add('pause');
                    verseElement.classList.add('active');

                    currentAudio.onended = () => {
                        verseElement.classList.remove('active');
                        currentAyahIndex++;
                        if (currentAyahIndex < ayahs.length) {
                            playSurah();
                        } else {
                            stopSurah();
                        }
                    };
                } catch (error) {
                    console.error('خطأ في تشغيل الصوت:', error);
                    document.getElementById('verses').innerHTML = '<p class="error">فشل تشغيل الصوت. تأكد من إعدادات المتصفح وجرب مرة أخرى.</p>';
                    stopSurah();
                }
            }
        }

        // إيقاف السورة
        function stopSurah() {
            if (currentAudio) {
                currentAudio.pause();
                currentAudio = null;
            }
            isPlayingSurah = false;
            currentAyahIndex = 0;
            const playSurahButton = document.getElementById('playSurahButton');
            playSurahButton.textContent = 'تشغيل السورة';
            playSurahButton.classList.remove('pause');
            document.querySelectorAll('.verse').forEach(verse => {
                verse.classList.remove('active');
            });
        }
    </script>
</body>
</html>
