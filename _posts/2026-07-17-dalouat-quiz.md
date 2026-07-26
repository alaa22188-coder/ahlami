---
layout: post
title: "اختبار الدلوعات الترفيهي: اكتشفي نسبة الدلع والرفاهية لديكِ!"
date: 2026-07-17
permalink: /dalouat-quiz/
category: "games"
description: "جرّبي اختبار الدلوعات الترفيهي الممتع المكون من 15 سؤالاً تفاعلياً لتكتشفي نسبة الدلع والرفاهية في شخصيتكِ فوراً."
---

<style>
    .quiz-container {
        background: #fff5f7;
        padding: 25px;
        border-radius: 15px;
        border: 2px solid #ffb6c1;
        box-shadow: 0 4px 15px rgba(255, 182, 193, 0.2);
        margin: 20px 0;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    .question-block {
        background: #ffffff;
        padding: 15px;
        border-radius: 10px;
        margin-bottom: 20px;
        border-right: 5px solid #ff69b4;
        box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    .question-text {
        font-size: 18px;
        font-weight: bold;
        color: #d81b60;
        margin-bottom: 12px;
    }
    .options-list {
        list-style: none;
        padding: 0;
        margin: 0;
    }
    .options-list li {
        margin-bottom: 8px;
        border: none;
        padding: 0;
    }
    .options-list label {
        display: block;
        padding: 10px 15px;
        background: #fff0f3;
        border: 1px solid #ffe0e6;
        border-radius: 8px;
        cursor: pointer;
        transition: all 0.2s ease;
    }
    .options-list label:hover {
        background: #ffe0e6;
        border-color: #ff69b4;
    }
    .options-list input[type="radio"] {
        margin-left: 10px;
        accent-color: #ff69b4;
    }
    .submit-btn {
        display: block;
        width: 100%;
        background: #ff69b4;
        color: white;
        border: none;
        padding: 15px;
        font-size: 18px;
        font-weight: bold;
        border-radius: 10px;
        cursor: pointer;
        box-shadow: 0 4px 10px rgba(255, 105, 180, 0.3);
        transition: background 0.3s;
    }
    .submit-btn:hover {
        background: #e0529c;
    }
    #result-box {
        display: none;
        background: #e8f5e9;
        border: 2px solid #81c784;
        padding: 20px;
        border-radius: 15px;
        text-align: center;
        margin-top: 25px;
    }
    #result-title {
        font-size: 24px;
        color: #2e7d32;
        font-weight: bold;
        margin-bottom: 10px;
    }
    #result-text {
        font-size: 18px;
        color: #43a047;
    }
</style>

أهلاً بكم في هذا الاختبار الترفيهي الخفيف! جاوبي على الـ 15 سؤالاً التالية بصراحة واكتشفي في النهاية ما إذا كنتِ "ملكة الدلع والرفاهية" أم أنكِ شخصية عملية وجادة جداً!

<div class="quiz-container">
    <form id="quizForm">
        <!-- السؤال 1 -->
        <div class="question-block">
            <p class="question-text">1. عندما تستيقظين في الصباح، ما هو أول شيء تفعلينه؟</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q1" value="3"> أظل في السرير لنصف ساعة لتعديل المزاج.</label></li>
                <li><label><input type="radio" name="q1" value="2"> أتفقد هاتفي سريعاً ثم أنهض.</label></li>
                <li><label><input type="radio" name="q1" value="1"> أنهض فوراً لبدء مهامي بنشاط جاد.</label></li>
            </ul>
        </div>
        <!-- السؤال 2 -->
        <div class="question-block">
            <p class="question-text">2. كيف تفضلين شرب قهوتك أو مشروبك المفضل؟</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q2" value="3"> في كوب مخصص أنيق، مع رغوة كثيفة وشوكولاتة مفرومة.</label></li>
                <li><label><input type="radio" name="q2" value="2"> كوب عادي سريع للتركيز فقط.</label></li>
                <li><label><input type="radio" name="q2" value="1"> أشرب أي شيء متوفر، لا يهمني الشكل.</label></li>
            </ul>
        </div>
        <!-- السؤال 3 -->
        <div class="question-block">
            <p class="question-text">3. إذا شعرتِ بملل خفيف أثناء العمل أو الدراسة:</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q3" value="3"> آخذ استراحة فورية للتسوق الإلكتروني أو العناية ببشرتي.</label></li>
                <li><label><input type="radio" name="q3" value="2"> أغير النشاط لشيء آخر مفيد.</label></li>
                <li><label><input type="radio" name="q3" value="1"> أضغط على نفسي وأكمل العمل حتى النهاية.</label></li>
            </ul>
        </div>
        <!-- السؤال 4 -->
        <div class="question-block">
            <p class="question-text">4. ما هو رد فعلكِ إذا انكسر أحد أظافركِ فجأة؟</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q4" value="3"> مأساة حقيقية! قد يتغير مزاجي طوال اليوم وأحجز موعد صالون فوراً.</label></li>
                <li><label><input type="radio" name="q4" value="2"> أنزعج قليلاً ثم أقصه بالمبرد وأنسى الأمر.</label></li>
                <li><label><input type="radio" name="q4" value="1"> أمر عادي جداً، لا أهتم بهذه التفاصيل.</label></li>
            </ul>
        </div>
        <!-- السؤال 5 -->
        <div class="question-block">
            <p class="question-text">5. روتين العناية بالبشرة (Skin Care) بالنسبة لكِ هو:</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q5" value="3"> طقس مقدس يومي يحتوي على 5 خطوات على الأقل وعطور هادئة.</label></li>
                <li><label><input type="radio" name="q5" value="2"> غسول ومرطب سريع عند التذكر.</label></li>
                <li><label><input type="radio" name="q5" value="1"> أغسل وجهي بالماء والصابون العادي وخلاص.</label></li>
            </ul>
        </div>
        <!-- السؤال 6 -->
        <div class="question-block">
            <p class="question-text">6. عند التخطيط للخروج مع الصديقات، أهم شيء هو:</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q6" value="3"> مكان هادئ، ديكوره "إنستغرامي" لالتقاط صور جميلة بملابس أنيقة.</label></li>
                <li><label><input type="radio" name="q6" value="2"> مكان يقدم طعاماً لذيذاً وجلسة مريحة.</label></li>
                <li><label><input type="radio" name="q6" value="1"> أي مكان نتجمع فيه، لا يهم التفاصيل.</label></li>
            </ul>
        </div>
        <!-- السؤال 7 -->
        <div class="question-block">
            <p class="question-text">7. كيف تتصرفين عندما يرفض أحدهم طلباً لكِ؟</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q7" value="3"> أستخدم أسلوب العتاب الرقيق والدلع حتى يوافق في النهاية.</label></li>
                <li><label><input type="radio" name="q7" value="2"> أحاول النقاش بالإقناع والمنطق.</label></li>
                <li><label><input type="radio" name="q7" value="1"> أتقبل الرفض ببرود وأعتمد على نفسي تماماً.</label></li>
            </ul>
        </div>
        <!-- السؤال 8 -->
        <div class="question-block">
            <p class="question-text">8. ملابس المنزل المفضلة لديكِ هي:</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q8" value="3"> بيجامات حريرية أو ساتان ناعمة بألوان زاهية متناسقة.</label></li>
                <li><label><input type="radio" name="q8" value="2"> ملابس قطنية مريحة وعملية للحركة.</label></li>
                <li><label><input type="radio" name="q8" value="1"> أي ملابس قديمة وواسعة تفي بالغرض.</label></li>
            </ul>
        </div>
        <!-- السؤال 9 -->
        <div class="question-block">
            <p class="question-text">9. عندما تسمعين كلمة "مطبخ وطبخ":</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q9" value="3"> أفضل الدليفري أو الأكلات الجاهزة الخفيفة لكي لا تفسد رائحة ملابسي.</label></li>
                <li><label><input type="radio" name="q9" value="2"> أطبخ عندما أكون في مزاج جيد وبوصفات سريعة.</label></li>
                <li><label><input type="radio" name="q9" value="1"> أدخل وأتولى الطبخ اليومي وغسيل الأطباق بكل جدية وبدون شكوى.</label></li>
            </ul>
        </div>
        <!-- السؤال 10 -->
        <div class="question-block">
            <p class="question-text">10. درجة استخدامك للإيموجيز (Emojis) مثل (🎀, ✨, 💖) في المحادثات:</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q10" value="3"> لا تخلو جملة واحدة أكتبها من القلوب واللمعات الوردية.</label></li>
                <li><label><input type="radio" name="q10" value="2"> أستخدمها بشكل طبيعي ومتوازن.</label></li>
                <li><label><input type="radio" name="q10" value="1"> نادراً ما أستخدمها، أسلوبي في الكتابة رسمي وجاد.</label></li>
            </ul>
        </div>
        <!-- السؤال 11 -->
        <div class="question-block">
            <p class="question-text">11. كيف تقضين عطلة نهاية الأسبوع المثالية؟</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q11" value="3"> في سبا (Spa)، تلوين أظافر، ومشاهدة أفلام رومانسية مع شموع عطرة.</label></li>
                <li><label><input type="radio" name="q11" value="2"> الخروج مع العائلة أو الصديقات لتغيير الجو.</label></li>
                <li><label><input type="radio" name="q11" value="1"> تنظيم البيت، غسيل الملابس، والتحضير للأسبوع القادم.</label></li>
            </ul>
        </div>
        <!-- السؤال 12 -->
        <div class="question-block">
            <p class="question-text">12. إذا رأيتِ حشرة صغيرة جداً في الغرفة (مثل فراشة أو نملة طائرة):</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q12" value="3"> أصرخ برقة وأنادي أي شخص فوراً لإنقاذي.</label></li>
                <li><label><input type="radio" name="q12" value="2"> أبتعد عنها وأنتظر حتى تخرج من النافذة.</label></li>
                <li><label><input type="radio" name="q12" value="1"> أحضر المبيد أو أطردها بنفسي فوراً وبدون تردد.</label></li>
            </ul>
        </div>
        <!-- السؤال 13 -->
        <div class="question-block">
            <p class="question-text">13. المشتريات التي تضعف ميزانيتكِ دائماً هي:</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q13" value="3"> العطور، مستحضرات التجميل، والإكسسوارات اللامعة.</label></li>
                <li><label><input type="radio" name="q13" value="2"> الملابس العملية والأحذية المريحة.</label></li>
                <li><label><input type="radio" name="q13" value="1"> الأدوات والكتب والأشياء المفيدة للمستقبل.</label></li>
            </ul>
        </div>
        <!-- السؤال 14 -->
        <div class="question-block">
            <p class="question-text">14. نبرة صوتكِ أثناء الحديث في الهاتف مع المقربين:</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q14" value="3"> هادئة، رقيقة، وتلقائياً تخرج ببعض النبرات الدلوعة.</label></li>
                <li><label><input type="radio" name="q14" value="2"> نبرة عادية طبيعية ومرحة.</label></li>
                <li><label><input type="radio" name="q14" value="1"> نبرة سريعة، واضحة، ومباشرة للدخول في الموضوع.</label></li>
            </ul>
        </div>
        <!-- السؤال 15 -->
        <div class="question-block">
            <p class="question-text">15. عندما يقدم لكِ شخص هدية مغلفة بشكل أنيق جداً:</p>
            <ul class="options-list">
                <li><label><input type="radio" name="q15" value="3"> أتحمس بشدة، أصور الغلاف أولاً، وأفتحها برقة وعناية شديدة.</label></li>
                <li><label><input type="radio" name="q15" value="2"> أفرح بها وأفتحها بفضول طبيعي.</label></li>
                <li><label><input type="radio" name="q15" value="1"> أقول شكراً وأفتحها بسرعة للاطلاع على المضمون.</label></li>
            </ul>
        </div>

        <button type="button" class="submit-btn" onclick="calculateResult()">احسبي نسبة الدلع الآن! ✨</button>
    </form>

    <div id="result-box">
        <p id="result-title"></p>
        <p id="result-text"></p>
    </div>
</div>

<script>
function calculateResult() {
    const form = document.getElementById('quizForm');
    const qCount = 15;
    let score = 0;
    let allAnswered = true;

    for (let i = 1; i <= qCount; i++) {
        const checkedOption = form.querySelector(`input[name="q${i}"]:checked`);
        if (checkedOption) {
            score += parseInt(checkedOption.value);
        } else {
            allAnswered = false;
            break;
        }
    }

    if (!allAnswered) {
        alert("لطفاً، جاوبي على جميع الأسئلة الـ 15 أولاً لظهور النتيجة! ✨");
        return;
    }

    const resultBox = document.getElementById('result-box');
    const resultTitle = document.getElementById('result-title');
    const resultText = document.getElementById('result-text');

    resultBox.style.display = "block";

    if (score >= 38) {
        resultTitle.innerHTML = "👑 ملكة الدلع والرفاهية المطلقة (نسبة الدلع 90% - 100%)";
        resultText.innerHTML = "أنتِ دلال يمشي على الأرض! تعشقين الرفاهية والأناقة، والاهتمام بأدق التفاصيل الأنثوية. الحياة بالنسبة لكِ يجب أن تكون ناعمة ووردية ومريحة دائماً.";
        resultBox.style.borderColor = "#ff69b4";
        resultBox.style.backgroundColor = "#fff0f3";
        resultTitle.style.color = "#d81b60";
    } else if (score >= 23 && score < 38) {
        resultTitle.innerHTML = "🌸 دلع متوازن وناعم (نسبة الدلع 50% - 85%)";
        resultText.innerHTML = "أنتِ تجمعين بين الدلع اللطيف والعقلانية العملية! تعرفين متى تدللين نفسكِ وتأخذين قسطاً من الرفاهية، ومتى تتحملين المسؤولية وتكونين جادة عند الحاجة. شخصيتكِ مريحة جداً ومحبوبة.";
        resultBox.style.borderColor = "#ffb6c1";
        resultBox.style.backgroundColor = "#fffdf9";
        resultTitle.style.color = "#e0529c";
    } else {
        resultTitle.innerHTML = "🛠️ شخصية عملية وجادة جداً (نسبة الدلع أقل من 45%)";
        resultText.innerHTML = "الدلع ليس في قاموسكِ اليومي! أنتِ امرأة عملية، قوية، وتفضلين الإنجاز والاعتماد على النفس على المظاهر والرفاهية الزائدة. حل المشكلات ومواجهة الواقع هو أسلوب حياتكِ.";
        resultBox.style.borderColor = "#90caf9";
        resultBox.style.backgroundColor = "#e3f2fd";
        resultTitle.style.color = "#1565c0";
    }

    // تدوير الصفحة لأسفل لعرض النتيجة تلقائياً
    resultBox.scrollIntoView({ behavior: 'smooth' });
}
</script>
