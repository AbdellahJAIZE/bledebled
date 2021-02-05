<template>
  <section class="product-details-area mtb-60px">
    <div class="container">
      <div class="row">
        <div class="col-xl-6 col-lg-6 col-md-12">
          <div class="product-details-img product-details-tab">
            <div class="zoompro-wrap zoompro-2">
              <div class="zoompro-border zoompro-span">
                <img
                  class="zoompro"
                  src="assets/images/product-image/tawfik/1.jpg"
                  data-zoom-image="assets/images/product-image/tawfik/1.jpg"
                  alt=""
                />
              </div>
            </div>
            <div id="gallery" class="product-dec-slider-2">
              <a
                class="active"
                data-image="assets/images/product-image/tawfik/1.jpg"
                data-zoom-image="assets/images/product-image/tawfik/1.jpg"
              >
                <img
                  src="assets/images/product-image/tawfik/1.jpg"
                  alt=""
                />
              </a>
              
              <a
                data-image="assets/images/product-image/tawfik/1.jpg"
                data-zoom-image="assets/images/product-image/tawfik/1.jpg"
              >
                <img
                  src="assets/images/product-image/tawfik/1.jpg"
                  alt=""
                />
              </a>
              <a
                data-image="assets/images/product-image/tawfik/1.jpg"
                data-zoom-image="assets/images/product-image/tawfik/1.jpg"
              >
                <img
                  src="assets/images/product-image/tawfik/1.jpg"
                  alt=""
                />
              </a>
            </div>
          </div>
        </div>
        <div class="col-xl-6 col-lg-6 col-md-12">
          <div class="product-details-content">
            <h2>{{article.nameFr}}</h2>
            <p class="reference">Reference:<span> {{ article.id }} </span></p>
            <div class="pro-details-rating-wrap">
              <div class="rating-product">
                <i class="ion-android-star"></i>
                <i class="ion-android-star"></i>
                <i class="ion-android-star"></i>
                <i class="ion-android-star"></i>
                <i class="ion-android-star"></i>
              </div>
              
            </div>
            <div class="pricing-meta">
              <ul>
                <li class="old-price not-cut">{{ article.priceMax }} MAD</li>
              </ul>
            </div>
            <div class="pro-details-list">
              <ul>
                
                <li>- {{ article.categoryFr }}</li>
                <li>- {{ article.wheght }}</li>
                
              </ul>
            </div>
            <div class="pro-details-quality mt-0px">
              <div class="cart-plus-minus">
                <input
                  class="cart-plus-minus-box"
                  type="text"
                  name="qtybutton"
                  value="1"
                />
              </div>
              <div class="pro-details-cart btn-hover">
                <a > +212 6 0000000</a>
              </div>
            </div>
            <div class="pro-details-wish-com">
              
            </div>
            <div class="pro-details-social-info">
              <span>Share</span>
              <div class="social-info">
                <ul>
                  <li>
                    <a href="#"><i class="ion-social-facebook"></i></a>
                  </li>
                  <li>
                    <a href="#"><i class="ion-social-twitter"></i></a>
                  </li>
                  <li>
                    <a href="#"><i class="ion-social-google"></i></a>
                  </li>
                  <li>
                    <a href="#"><i class="ion-social-instagram"></i></a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="pro-details-policy">
              <ul>
                <li>
                  <img src="assets/images/icons/policy.png" alt="" /><span
                    >Security Policy </span
                  >
                </li>
                <li>
                  <img src="assets/images/icons/policy-2.png" alt="" /><span
                    >Delivery Policy </span
                  >
                </li>
                <li>
                  <img src="assets/images/icons/policy-3.png" alt="" /><span
                    >Return Policy </span
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
//import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: "Blank",
  data() {
    return {
      article: {
        id: 1,
        nameFr: "Couscous Complet",
        nameAr: "كسكس القمح الكامل ",
        bioFR:
          "·Le couscous de blé entier est une excellente source de vitamines qui aident à augmenter les niveaux d’énergie corporelle et à améliorer les fonctions cérébrales. Il est également riche en glucides qui sont une excellente source d’énergie dont le corps a besoin pour les activités quotidiennes .lors de la cuisson du couscous, petit grain de pâte devient un peu plus grand et adoucissant, Ils sont généralement cuits avec des légumes et de la viande pour un plat plein et nutritif.",
        bioAr:
          "يعد  كسكس القمح الكامل  مصدراً ممتازاً لمجموعة من الفيتامينات، التي تساعد على زيادةمستويات الطاقة في الجسم وتحسين وظائف الدماغ. وكذالك التخفيف من حدة الالتهابات المزمنة.،والحماية من سرطان القولون.وحماية الأطفال من الربو، كما أنه غني  بالكربوهيدرات التي هي مصدر ممتاز للطاقة التي يحتاجها الجسم لممارسة الأنشطة اليومية.عند طهو الكسكس فإن الحبات الصغيرة من العجين تزداد حجماً بعض الشيء وتصبح لينة ولذيذة، وعادة ما يطهى إلى جانب الخضراوات واللحم لطبق متكامل غني بالمواد الغذائية",
        priceMax: "25",
        priceMin: "22,5",
        categoryFr: "couscous",
        categoryAr: "كسكس",
        wheght: "1kg",
      },
      Articles: [
        {
          id: 1,
          nameFr: "Couscous Complet",
          nameAr: "كسكس القمح الكامل ",
          bioFR:
            "·Le couscous de blé entier est une excellente source de vitamines qui aident à augmenter les niveaux d’énergie corporelle et à améliorer les fonctions cérébrales. Il est également riche en glucides qui sont une excellente source d’énergie dont le corps a besoin pour les activités quotidiennes .lors de la cuisson du couscous, petit grain de pâte devient un peu plus grand et adoucissant, Ils sont généralement cuits avec des légumes et de la viande pour un plat plein et nutritif.",
          bioAr:
            "يعد  كسكس القمح الكامل  مصدراً ممتازاً لمجموعة من الفيتامينات، التي تساعد على زيادةمستويات الطاقة في الجسم وتحسين وظائف الدماغ. وكذالك التخفيف من حدة الالتهابات المزمنة.،والحماية من سرطان القولون.وحماية الأطفال من الربو، كما أنه غني  بالكربوهيدرات التي هي مصدر ممتاز للطاقة التي يحتاجها الجسم لممارسة الأنشطة اليومية.عند طهو الكسكس فإن الحبات الصغيرة من العجين تزداد حجماً بعض الشيء وتصبح لينة ولذيذة، وعادة ما يطهى إلى جانب الخضراوات واللحم لطبق متكامل غني بالمواد الغذائية",
          priceMax: "25",
          priceMin: "22,5",
          categoryFr: "couscous",
          categoryAr: "كسكس",
          wheght: "1kg",
        },
        {
          id: 2,
          nameFr: "Couscous d'orge ",
          nameAr: "كسكس بالشعير البلدي",
          bioFR:
            "L’orge contient un grand nombre de fibres alimentaires, de vitamines et de minéraux qui réduisent l’hypertension artérielle, aident à contrôler le poids et à garder les os en santé et renforcés. L’orge est la meilleure option pour maintenir la santé cardiaque afin qu’elle réduise le taux de cholestérol sanguin et vous protège ainsi des différentes maladies cardiaques. Il aide également à organiser la digestion du corps en raison de sa fibre alimentaire importante du système digestif, qui vous protège de la constipation et aide à réguler le mouvement intestinal.",
          bioAr:
            "يحتوي الشعير على عدد كبير من الألياف الغذائية والفيتامينات والمعادن ، التي تعمل على خفض ضغط الدم العالي، وتساعد على التحكم  بالوزن ,كما تحافظ  على صحة العظام وتقويها. ويعد الشعير الخيار الأمثل للحفاظ على صحة القلب بحيث يخفض من مستوى الكوليسترول بالدم وبالتالي حمايتك من الإصابة بأمراض القلب المختلفة. كما يساعد في تنظيم عملية الهضم بالجسم بسبب احتواءه على الألياف الغذائية المهمة للجهاز الهضمي، هذه الأخيرة تحميك من الإصابة بالإمساك، وتساعد في تنظيم عملية حركة الأمعاء",
          priceMax: "25",
          priceMin: "22,5",
          categoryFr: "couscous",
          categoryAr: "كسكس",
          wheght: "1kg",
        },
        {
          id: 3,
          nameFr: "Couscous de Quinoa Municipalité",
          nameAr: "كسكس بالدرة بلدية",
          bioFR:
            "Le maïs jaune aide à réduire le poids supplémentaire, car il contient beaucoup de calories.\nIl contient également une grande proportion de fibres qui aide à sentir la saturation\nLe maïs contient des minéraux, comme le potassium, qui aident à réguler la pression artérielle, et le manganèse, qui régule les fonctions cérébrales et nerveuses.\n",
          bioAr:
            "تساعد الذرة الصفراء على إنقاص الوزن الزائد، وهذا لأنها تحتوي على الكثير من السعرات الحرارية.\nكما تحتوى على نسبة كبيرة من الألياف التي تساعد على الشعور بالشبع.وتعتبر غري بالكربوهيدرات المهمة لطاقة الجسم.وهي مصدر غنيّ بالألياف\nوتحتوي الذرة على بعض المعادن، مثل البوتاسيوم والذي يساعد على تنظيم ضغط الدم، والمنغنيز الذي يدخل في تنظيم وظائف الدماغ والأعصاب.\n",
          priceMax: "25",
          priceMin: "22,5",
          categoryFr: "couscous",
          categoryAr: "كسكس",
          wheght: "1kg",
        },
        {
          id: 4,
          nameFr: "Couscous D’orge Commune et D'avoine cultivee",
          nameAr: "كسكس الخرطال والشعير",
          bioFR:
            "Une combinaison de deux éléments très importants pour le corps, les fibres contenues dans l’orge aident à se sentir rassasié sans ajouter de calories supplémentaires, ce qui rend l’orge particulièrement important pour ceux qui veulent perdre du poids supplémentaire. L’avoine aide également à réduire le poids, avec des fibres solubles qui donnent une sensation de saturation.\nLe cholestérol et le glucose sont réduits dans le sang.\nL’avoine est considérée comme un bon antioxydant, car elle contient un pourcentage élevé de polyphénol qui agit comme un antioxydant de la graisse dans le corps.\n",
          bioAr:
            "مزيج من عنصرين مهمين جدا للجسم،تساعد الألياف التي يحتوي عليها الشعير على الشعور بالشبع دون إضافة أية سعرات حرارية إضافية، ما يجعل الشعير هاماً بشكل خاص لمن يرغبون في خسارة الوزن الزائد. كما يساعد الشوفان في تخفيض الوزن أيضا، لاحتوائه على أليافٍ قابلة للذوبان تعطي إحساساً بالشبع.\nويقلل نسبة الكوليسترول والجلوكوز في الدم.\nويعتبر الشوفان مضادٌ جيدٌ للأكسدة، لاحتوائه على نسبة عالية من البوليفينول الذي يعمل كمضاد لتأكسد الشحوم في الجسم.\n",
          priceMax: "25",
          priceMin: "22,5",
          categoryFr: "couscous",
          categoryAr: "كسكس",
          wheght: "1kg",
        },
        {
          id: 5,
          nameFr: "Couscous Tolati",
          nameAr: "كسكس ثلاثي",
          bioFR:
            "La combinaison couscous tolati du couscous de blé complet et du couscous de maïs plus l’orge, qui nous donne une combinaison d’avantages naturels, il est riche en glucides, calories et vitamines, qui aident à augmenter les niveaux d’énergie dans le corps et améliorer les fonctions cérébrales.",
          bioAr:
            "كسكس الثلاثي مزيج بين كسكس القمح الكامل وكسكس الذرة إضافة إلى الشعير،الذي يعطينا مزيج من  الفوائد الطبيعة والغنية بالكربوهيدرات والسعرات الحرارية والفيتامينات ، التي تساعد على زيادةمستويات الطاقة في الجسم وتحسين وظائف الدماغ.",
          priceMax: "25",
          priceMin: "22,5",
          categoryFr: "couscous",
          categoryAr: "كسكس",
          wheght: "1kg",
        },
        {
          id: 6,
          nameFr: "Couscous Khomasi",
          nameAr: "كسكس خماسي",
          bioFR:
            "Il se compose de plusieurs éléments très importants : Le blé, le maïs et l’orge, ainsi que le millet et l’orge rouge, nous donnant un mélange que notre corps a besoin sur une base quotidienne, le couscous khoumasi est un repas complet pour ceux qui recherchent beaucoup d’avantage dans un seul aliment.",
          bioAr:
            "يحتوي كسكس الخماسي على خمس عناصر مهمة جدا وهي القمح والذرة والشعير إضافة إلى الدخن والشعير المحمر ،ما يعطينا مزيجا من الفوائد المهمة التي يحتاجها جسمنا بشكل يومي،كسكس الخماسي يعتبر وجبة كاملة لمن يبحث عن فوايد كثيرة في أكلة واحدة.",
          priceMax: "25",
          priceMin: "22,5",
          categoryFr: "couscous",
          categoryAr: "كسكس",
          wheght: "1kg",
        },
        {
          id: 7,
          nameFr: "Couscous de blé au Quinoa",
          nameAr: "كسكس القمح بالكينوا",
          bioFR:
            "Le couscous de blé quinoa est une combinaison de deux éléments très importants. Nous savons tous que les grains de blé entier sont une excellente source de vitamines qui aident à augmenter les niveaux d’énergie dans le corps et à améliorer les fonctions cérébrales.\nLe blé est également riche en glucides, une excellente source d’énergie dont le corps a besoin pour les activités quotidiennes. Quinoa contient des fibres et des glucides sains, qui ont un rôle dans l’augmentation de la sensation de saturation, et les haricots quinoa aider à brûler les graisses accumulées dans le corps. Cela diminue l’excès de poids.\n",
          bioAr:
            "كسكس القمح بالكينوا مزيج لعنصرين مهمين جدا وفوائد مذهلة فكلنا نعرف أن حبوب القمح الكاملة  تعتبر مصدراً ممتازاً لمجموعة من الفيتامينات، التي تساعد على زيادةمستويات الطاقة في الجسم وتحسين وظائف الدماغ.\nكما أن القمح غني  بالكربوهيدرات التي هي مصدر ممتاز للطاقة التي يحتاجها الجسم لممارسة الأنشطة اليومية.والكينوا تحتوي على الألياف الصحية والكربوهيدرات، والتي لها دور في زيادة الشعور بالشبع، ما يقلل من تناول كميات الطعام، بالإضافة إلى أن حبوب الكينوا تساعد على حرق الدهون المتراكمة بالجسم، ما يساهم في إنقاص الوزن الزائد.\n",
          priceMax: "25",
          priceMin: "22,5",
          categoryFr: "couscous",
          categoryAr: "كسكس",
          wheght: "1kg",
        },
        {
          id: 8,
          nameFr: "Couscous de Quinoa Municipalité",
          nameAr: "كسكس كينوا  البادية ",
          bioFR:
            "Le quinoa est une source de minéraux, de vitamines et de protéines,  il est très important de prévenir le cancer et de garder le cœur en santé. Il aide également à réduire la fatigue. Il est aussi utile que cela pour renforcer les os parce qu’il a un rapport élevé de calcium, aidant à protéger contre l’ostéoporose, et aussi à construire les muscles et les os bien.",
          bioAr:
            "تعتبر الكينوا مصدر للمعادن  والفيتامينات والبروتينات،ولها فوائد كثيرة ومهمة منهاالحماية من السرطان والحفاظ على صحة القلب وكذالك تقوية الجهاز المناعي:لوجود عناصر غذائية متعددة في حبوب الكينوا فإنها تساعد على تقوية الجهاز المناعي، ما يقي من التعرض للأمراض المتعلقة به، بالإضافة إلى أنها تساعد على التخفيف من الشعور بالتعب والإجهاد.ومفيدة كذالك لتقوية العظام لاحتوائها على نسبة عالية من الكالسيوم، ما يساعد على الحماية من الإصابة بمرض هشاشة العظام، وتساعد على بناء العضلات والعظام بشكل جيد.",
          priceMax: "25",
          priceMin: "22,5",
          categoryFr: "couscous",
          categoryAr: "كسكس",
          wheght: "1kg",
        },
        {
          id: 9,
          nameFr: "Folcans d'avoine",
          nameAr: "رقائق الشوفان",
          bioFR:
            "Améliore le système immunitaire. Il est très riche de protéines végétales qui construisent les muscles nécessaires pour construire un corps fort pour les enfants au début de leur structure corporelle. C’est une source d’énergie propre pour les enfants pour toutes leurs activités quotidiennes, et il est très utile pour les adultes de contenir des fibres solubles donne une sensation de saturation.\nLe cholestérol et le glucose sont réduits dans le sang.\nL’avoine est un bon antioxydant, car il contient un pourcentage élevé de polyphénol qui agit comme un antioxydant de la graisse dans le corps.\n",
          bioAr:
            "يعزز الجهاز المناعي، وهو ما يحتاجه الأطفال جدًا حتى يتجنبوا جميع الأمراض المتخخصة في مهاجمة الأطفال،كما يعتبر مصدر غني بالبروتين النباتي وهو ما يقوم ببناء العضلات اللازمة لبناء جسد قوي للأطفال في بداية العمليّة البنائيّة لأجسادهم في صغرهم.وهو مصدر نظيف للطاقة اللازمة للأطفال لجميع أنشطتهم اليوميّة،كما هو مفيد جدا للكبار لاحتوائه على أليافٍ قابلة للذوبان تعطي إحساساً بالشبع.\nويقلل نسبة الكوليسترول والجلوكوز في الدم.\nويعتبر الشوفان مضادٌ جيدٌ للأكسدة، لانه يحتوي على نسبة عالية من البوليفينول الذي يعمل كمضاد لتأكسد الشحوم في الجسم.\n\n",
          priceMax: "30",
          priceMin: "27",
          categoryFr: "Avoine",
          categoryAr: "الشوفان",
          wheght: "900g",
        },
        {
          id: 10,
          nameFr: "Farine D'orge",
          nameAr: "دقيق الشعير البلدي",
          bioFR:
            "L’orge aide à maintenir la santé de l’intestin et protège contre les calculs biliaire, en raison de sa forte teneur en fibres alimentaires, qui aide à réduire les acides qui sont   accumulés et qui peuvent causer les calculs biliaire. L’orge est riche en divers antioxydants. Cela réduit les risques de cancer et les risques de maladies cardiaques et d’infections en général.\nLa fibre alimentaire dans l’orge aide à contrôler et à réduire le taux de mauvais cholestérol dans le corps, et les médecins recommandent de prendre l’orge surtout en raison de sa très faible teneur en gras et complètement exempt de cholestérol.\n",
          bioAr:
            "يحافط الشعير على صحة الأمعاء ويحمي من الإصابة بحصى المرارة بسبب إحتواءه على كمية عالية من الألياف الغدائية التي تساعد على التقليل من الأحماض التي يتم إفرازها وتراكمها على مستوى...و يحتوي الشعير أيضا على العديد من مضادات الأكسدة التي تقلل من الضرر الذي تسببه الجذور الحرة في الجسم و التي تتسبب في ظهور أمراض القلب و الأوعية الدموية وبعض أنواع السرطان وأمراض أخرى مرتبطة بالشيخوخة. وتساعد الألياف الغذائية الموجودة في الشعير أيضا على السيطرة على مستويات الكوليسترول السيء في الجسم و تساهم في خفضها، ويوصي الأطباء بتناول الشعير بشكل خاص بسبب محتواه القليل جداً من الدهون وخلوه التام من الكوليسترول.  ",
          priceMax: "19",
          priceMin: "17,1",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "1kg",
        },
        {
          id: 11,
          nameFr: "Farine de soja",
          nameAr: "دقيق الصوجا",
          bioFR:
            "La farine de soja a tous les huit acides aminés essentiels pour le corps humain de faire des protéines, ce qui en fait une source de protéines complètes. Il aide à augmenter l’activité corporelle et le poids en stimulant le corps à produire des protéines et contribue à une augmentation significative de l’appétit et une ouverture claire du corps en contenant des fibres qui aident à stimuler le fonctionnement du système digestif, créant ainsi une plus grande sensation de saturation et de manger et de conserver l’énergie emmagasinée dans le corps",
          bioAr:
            "يمتاز دقيق الصوجا باحتوائه على جميع الأحماض الأمينية الأساسية الثمانية الضرورية لجسم الإنسان لصنع البروتين، مما يجعله من المصادر الغنية بالبروتين الكامل, يساعد على زيادة نشاط الجسم و زيادة الوزن عن طريق تحفيز الجسم على إنتاج البروتين ويساهم في زيادة الشهية وفتحها بشكلٍ كبير وواضح لاحتوائهِ على الألياف التي تُساعد على تنشيط عمل الجهاز الهضميّ، وبالتالي عدم الإحساس بالشبع وتناول الطعام بشكلٍ أكبر كما يحافظ على الطاقة المُخزّنة في الجسم.",
          priceMax: "22",
          priceMin: "20",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "500g",
        },
        {
          id: 12,
          nameFr: "Farine des lentilles rouges",
          nameAr: "دقيق العدس الأحمر",
          bioFR:
            "Les lentilles sont une source d’énergie riche en glucides complexes et en fibres.\nIl est également riche en différents minéraux et vitamines, tels que le fer, le calcium, le phosphore, le magnésium et l’acide folique, qui aident à réguler le fonctionnement digestif et facilitent la digestion.\nEt la prévention de la constipation et des symptômes du côlon.\nEt de nombreux autres problèmes de santé liés à la régulation du poids, le diabète, et d’autres.\n",
          bioAr:
            "يعد العدس مصدراً للطاقة وغني بالكربوهيدرات المعقدة والألياف.\nويعتبر غنياً بالمعادن والفيتامينات المختلفة، مثل: الحديد والكالسيوم والفوسفور والمغنيسيوم وحمض الفوليك.يساعد على تنظيم عمل الجهاز الهضمي وتسهيل الهضم.\nوالوقاية من الامساك واعراض القولون العصبي.\nوالعديد من الامور الصحية الاخرى المتعلقة بتنظيم الوزن والسكري وغيرها.\n",
          priceMax: "24",
          priceMin: "20",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "500g",
        },
        {
          id: 13,
          nameFr: "Farine des haricots",
          nameAr: "دقيق الفول",
          bioFR:
            "Le haricot est un repas important pour le corps car il est riches en protéines, vitamines, minéraux essentiels, acide folique et phosphore, donc le corps est pourvu de tous les nutriments nécessaires.il résiste au stress.il donne une longue sensation de saturation. Il aide également à réduire le poids et à combattre le cancer en contenant des substances naturelles qui aident à prévenir la formation de tumeurs.Il réduit l’hypertension artérielle et renforce l’immunité du corps.Il régule le taux de glycémie. Il renforce également les os et aide à la formation de globules rouges",
          bioAr:
            "يعتبر الفول من الوجبات المهمة للجسم لأنه غني بالبروتينات والفيتامينات والمعادن الأساسية وحمض الفوليك والفوسفور، لذلك يمد الجسم بكل العناصر الغذائية المطلوبة.ويقاوم التوتر والإجهاد الذي يصيب الجسم بسبب احتوائه على البروتين وبعض الفيتامينات.ويعطى شعوراً بالشبع لفترة طويلة، كما يساعد على إنقاص الوزن.و يكافح السرطان لاحتواءه على مواد طبيعية تساعد فى منع تكون الأورام.و يخفض ضغط الدم المرتفع ويقوي مناعة الجسم.وينظم مستوى السكر فى الدم.كما أنه يقوي العظام ويساعد فى تكوين خلايا الدم الحمراء.",
          priceMax: "22",
          priceMin: "20",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "500g",
        },
        {
          id: 14,
          nameFr: "Farine de pain santé",
          nameAr: "دقيق الخبز الصحي",
          bioFR:
            "La farine de pain sain se compose de : farine d'orge, L'Avoine cultivée, farine de maïs, farine de pois chiche, farine de millet, farine de lentilles, sésame, anis, anis vert d’Espagne, nigelle, lin cultivé, papavéracées, farine blé complet, farine blé dur, graine de tournesol, Graine de courge, tous ces ingrédients rendre cette repas sain et intégré.",
          bioAr:
            "يتكون دقيق الخبز الصحي من :دقيق الشعير،دقيق الخرطال،دقيق الذرة،دقيق الحمص،دقيق الان،دقيق العدس،زنجلان،نافع،حبة حلاوة،السانوج،زريعة الكتان،الخشخاش،دقيق القمح الكامل،دقيق القمح الصلب،حبوب نوار الشمس،حبوب اليقطين.ما يجعله صحي بكل المقايس من أجل وجبة صحية ومتكاملة.\n\n",
          priceMax: "28",
          priceMin: "25,2",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "1kg",
        },
        {
          id: 15,
          nameFr: "Farine du Riz",
          nameAr: "دقيق الأرز",
          bioFR:
            "Le riz et le riz sont généralement considérés comme un produit alimentaire très important pour former une alimentation équilibrée dans tous ses éléments, et bien qu’il soit communément admis que le riz blanc provoque l’obésité, le riz organique et naturel à faible teneur en sodium, et la lutte contre l’obésité et le riz est une source d’énergie saine pour le corps. Il contient des glucides, qui sont essentiellement une source d’énergie majeure, avec un corps contenant 50% de calories par jour et un peu de sodium qui met la pression artérielle sous contrôle",
          bioAr:
            "يعتبر  كسكس الأرز والأرز بصفة عامة أحد الأصناف الغذائية الهامة جداً لتشكيل وجبة غذائية متوازنة في كافة عناصرها، ومع أن المعتقد الشائع هو أن الأرز الأبيض يسبب السمنة، إلا أن الأرز العضوي والطبيعي قليل الصوديوم والدهون يكافح السمنة كما يعتبر الأرز مصدراً صحياً لتزويد الجسد بالطاقة، إذ يحتوي على الكربوهيدرات والتي تعتبر بالأساس مصدر رئيسي للطاقة حيث يحصد الجسم ما مقداره 50% من السعرات الحرارية  يومياً.كما أنه يحتوي على قليل من الصوديم الذي يجعل ضغط الدم تحت السيطرة.",
          priceMax: "22",
          priceMin: "20",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "500g",
        },
        {
          id: 16,
          nameFr: "Farine d'avoine",
          nameAr: "دقيق الشوفان",
          bioFR:
            "Il protège contre les maladies cardiovasculaires, car il contient du bêta-glukkan, qui contribue à une réduction significative du cholestérol dans le sang et réduit le risque de maladies cardiovasculaires. L’avoine cultivée protège contre le cancer du côlon. Il contient de nombreux nutriments importants, il contient également une grande quantité de calcium qui aide à prendre soin des os et empêche l’élimination des minéraux d’entre eux, et il aide également à les renforcer et à prévenir leur fragilité. L’avoine est considérée comme un bon antioxydant, car ils contiennent un pourcentage élevé de polyphénol qui agit comme un antioxydant pour les lipides du corps.",
          bioAr:
            "يحمي من أمراض القلب الوعائية، لاحتوائه على البيتا غلوكان، بحيث تساهم هذه الأخيرة في خفض نسبة الكوليسترول في الدم بشكلٍ كبير ويؤدي إلى خفض خطر الإصابة بأمراض القلب الوعائية.للشوفان دورٌ في الحماية من مرض سرطان القولون.يحتوي على العديد من العناصر الغذائية المهمة، كالبروتينات والألياف الغذائية والمنغنيز والصوديوم.كما يحتوي الشوفان على كمية كبيرة من الكالسيوم الذي بساعد على العناية بالعظام و يمنع إزالة المعادن منها ، كما يعمل على تقويتها و منع هشاشتها.ويعتبر الشوفان مضادٌ جيدٌ للأكسدة، لانه يحتوي على نسبة عالية من البوليفينول الذي يعمل كمضاد لتأكسد الشحوم في الجسم.",
          priceMax: "22",
          priceMin: "20",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "900g",
        },
        {
          id: 17,
          nameFr: "Farine du Mais",
          nameAr: "دقيق الذرة البلدي",
          bioFR:
            "La farine de maïs contient une gamme de minéraux, comme le potassium, qui aident à réguler la pression artérielle et le manganèse qui régule les fonctions cérébrales et nerveuses. Le maïs aide à réduire le surpoids, car il contient beaucoup de calories.Il contient également une grande proportion de fibres qui aident à se sentir rassasié.Il est considéré comme un glucide aussi important pour l’énergie de l’organisme.C’est une source riche en fibres, et le maïs est une vitamine C-source riche; C’est un antioxydant qui contribue à maintenir les cellules du corps contre les dommages et à réduire le risque de certaines maladies comme le cancer et les maladies cardiaques",
          bioAr:
            "يحتوي دقيق الذرة على مجموعة من المعادن، مثل البوتاسيوم والذي يساعد على تنظيم ضغط الدم، والمنغنيز الذي يدخل في تنظيم وظائف الدماغ والأعصاب. تساعد الذرة الصفراء على إنقاص الوزن الزائد، وهذا لأنها تحتوي على الكثير من السعرات الحرارية.كما تحتوى على نسبة كبيرة من الألياف التي تساعد على الشعور بالشبع.وتعتبر غري بالكربوهيدرات المهمة لطاقة الجسم.وهي مصدر غنيّ بالألياف، بالإضافة إلى أنّ الذرة تعدّ من المصادر الغنيّة بفيتامين ج؛ وهو أحد مضادات الأكسدة التي تساهم في الحفاظ على خلايا الجسم من التلف، وتقليل خطر الاصابة ببعض الأمراض مثل السرطان وأمراض القلب",
          priceMax: "22",
          priceMin: "19,8",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "1kg",
        },
        {
          id: 18,
          nameFr: "Farine de point chiches",
          nameAr: "دقيق الحمص",
          bioFR:
            "Les pois chiches sont une excellente source végétale de protéines, et bien que les pois chiches soient faible en sodium, ils contiennent de grandes quantités d’autres minéraux, Une tasse de pois chiches cuits fournit 59% du fer nécessaire pour un adulte.améliore la santé du système digestif, aide à contrôler les niveaux de glycémie, et réduit le risque de maladie cardiaque.  \n\n",
          bioAr:
            "الحمص هو مصدر نباتي بروتيني ممتاز،وعلى الرغم من أن الحمص منخفض الصوديوم، لكنه يحتوي على كميات كبيرة من  المعادن العديدة الأخرى، حيث أن كوب واحد من الحمص المطبوخ يوفر 59% من كمية الحديد اللازمة لشخص بالغ.يعزز صحة الجهاز الهضمي كما يساعد في السيطرة على مستويات السكر في الدم،كما يقلل من خطر الإصابة بأمراض القلب،",
          priceMax: "22",
          priceMin: "19,8",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "500g",
        },
        {
          id: 19,
          nameFr: "Farine de Blé Complet",
          nameAr: "دقيق القمح الكامل",
          bioFR:
            "Le blé complet est une excellente source de vitamines qui aident à augmenter les niveaux d’énergie corporelle et à améliorer les fonctions cérébrales.\nIl est également riche en glucides, une excellente source d’énergie dont le corps a besoin pour les activités quotidiennes.\n",
          bioAr:
            "يعتبر القمح الكامل مصدراً ممتازاً لمجموعة من الفيتامينات، التي تساعد على زيادة مستويات الطاقة في الجسم وتحسين وظائف الدماغ.\nكما أنه غني  بالكربوهيدرات التي تعتبر مصدرا ممتاز للطاقة التي يحتاجها الجسم لممارسة الأنشطة اليومية.\n",
          priceMax: "20",
          priceMin: "18",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "1kg",
        },
        {
          id: 20,
          nameFr: "Farine de Mil",
          nameAr: "دقيق الدخن (إيلان)",
          bioFR:
            "Le millet contient des glucides jusqu'à 65%, y compris des sucres sans amidon et des fibres aide à réduire la constipation, ralentir la sécrétion de glucose sanguin, réduire le cholestérol sanguin, et est une source riche en minéraux. Le millet est riche en composés phytochimiques (en anglais : Phytochemicals). Il améliore la santé et l’immunité, est un antioxydant, et aide à détoxifier le corps, tels que : polyphénols, lignane, fitosterol, œstrogène botanique, et phénotocytocyanines.",
          bioAr:
            "يحتوي الدُّخن على الكربوهيدرات التي تُشكّل فيه نسبةً تصل إلى 65% بما فيها السكريات غير النشويّة والألياف؛ التي تساعد على تقليل الإمساك، وإبطاء إفراز الجلوكوز في الدم، وخفض نسبة الكوليسترول في الدم، بالإضافة لكونه مصدراً غنياً بالمعادن، كما يعد الدُّخن غنياً بالكيميائيات النباتية (بالإنجليزية: Phytochemicals)؛ التي تحسن الصحة والمناعة، وتعدّ من مضادات الأكسدة، وتساعد على طرح سموم الجسم، مثل: البوليفينولات، والليغنان (بالإنجليزية: Lignan)، والفايتوستيرول، والإستروجين النباتي، والفيتوسيانين (بالإنجليزية: Phytocyanins).",
          priceMax: "22",
          priceMin: "20",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "500g",
        },
        {
          id: 21,
          nameFr: "Hessoua Marocaine",
          nameAr: "دشيشة شعير خماسية",
          bioFR:
            "Pour un petit déjeuner naturel et complet, nous recommandons dchicha khomasiya (soupe khomasi) qui est un mélange d’orge naturel. En plus d’anis et nigelle, le lin cultivé et Le Cresson alénois. Les fibres alimentaires trouvée dans l’orge aide à contrôler et contribue à la réduction des taux de mauvais cholestérol dans le corps, et les médecins recommandent que l’orge soit consommée surtout en raison de sa très faible teneur en gras et complètement exempt de cholestérol.",
          bioAr:
            "من أجل فطور متكامل وطبيعي ننصحك بالدشيشة الخماسية(الحساء الخماسي)الذي هو مزيج من الشعير الطبيعي. إضافة إلى النافع البلدي والسانوج وزريعة الكتان وحب الرشاد. وتساعد الألياف الغذائية الموجودة في الشعير على السيطرة على مستويات الكوليسترول السيء في الجسم و تساهم في خفضها، ويوصي الأطباء بتناول الشعير بشكل خاص بسبب محتواه القليل جداً من الدهون وخلوه التام من الكوليسترول.",
          priceMax: "23",
          priceMin: "21",
          categoryFr: "Hssoua",
          categoryAr: "دشيشة",
          wheght: "1kg",
        },
        {
          id: 22,
          nameFr: "Hessoua Marocaine",
          nameAr: "دشيشة شعير متوسطة",
          bioFR:
            "En raison de sa forte teneur en fibres alimentaires, qui aide à réduire la quantité d’acide consommé et qui peut causer du gravier amer, il aide à protéger la santé du tractus intestinal contre l’infection du cœur et les maladies inflammatoires en général. Les médecins recommandent que l’orge soit mangé surtout en raison de sa très faible teneur en gras et complètement exempt de cholestérol",
          bioAr:
            'يساعد دشيش الشعير "قمح بلادي"للحفاظ على صحة الأمعاء وعلى الحماية من الإصابة بحصى المرارة، وذلك بسبب محتواه العالي من الألياف الغذائية والتي تساعد على التقليل من الأحماض التي يتم إفرازها وتراكمها والذي قد يتسبب في حصى المرارة.كما أن تناوله بانتظام يقلل من فرص الإصابة بأمراض القلب والالتهابات عموماً. ويوصي الأطباء بتناول الشعير بشكل خاص بسبب محتواه القليل جداً من الدهون وخلوه التام من الكوليسترول.',
          priceMax: "23",
          priceMin: "21",
          categoryFr: "Hssoua",
          categoryAr: "دشيشة",
          wheght: "1kg",
        },
        {
          id: 23,
          nameFr: "Hessoua Marocaine",
          nameAr: "دشيشة شعير غليضة",
          bioFR:
            "En raison de sa forte teneur en fibres alimentaires, qui aide à réduire la quantité d’acide consommé et qui peut causer du gravier amer, il aide à protéger la santé du tractus intestinal contre l’infection du cœur et les maladies inflammatoires en général. Les médecins recommandent que l’orge soit mangé surtout en raison de sa très faible teneur en gras et complètement exempt de cholestérol",
          bioAr:
            'يساعد دشيش الشعير "قمح بلادي"للحفاظ على صحة الأمعاء وعلى الحماية من الإصابة بحصى المرارة، وذلك بسبب محتواه العالي من الألياف الغذائية والتي تساعد على التقليل من الأحماض التي يتم إفرازها وتراكمها والذي قد يتسبب في حصى المرارة.كما أن تناوله بانتظام يقلل من فرص الإصابة بأمراض القلب والالتهابات عموماً. ويوصي الأطباء بتناول الشعير بشكل خاص بسبب محتواه القليل جداً من الدهون وخلوه التام من الكوليسترول.',
          priceMax: "23",
          priceMin: "21",
          categoryFr: "Hssoua",
          categoryAr: "دشيشة",
          wheght: "1kg",
        },
        {
          id: 24,
          nameFr: "Hessoua Marocaine",
          nameAr: "دشيشة درة بلدية رقيقة",
          bioFR:
            "La Dashisha de maïs contient une grande proportion de fibres qui aide à se sentir saturé.it est également riche en glucides qui sont importants pour l’énergie de l’organisme.C’est une source riche en fibres, et le maïs est une source riche en vitamine C; C’est un antioxydant qui contribue à maintenir les cellules du corps contre les dommages et à réduire le risque de certaines maladies comme le cancer et les maladies cardiaques",
          bioAr:
            "يحتوي دشيش الذرة على نسبة كبيرة من الألياف التي تساعد على الشعور بالشبع.كما أنها غنية بالكربوهيدرات المهمة لطاقة الجسم.وهي مصدر غنيّ بالألياف، بالإضافة إلى أنّ الذرة تعدّ من المصادر الغنيّة بفيتامين ج؛ وهو أحد مضادات الأكسدة التي تساهم في الحفاظ على خلايا الجسم من التلف، وتقليل خطر الاصابة ببعض الأمراض مثل السرطان وأمراض القلب",
          priceMax: "23",
          priceMin: "21",
          categoryFr: "Hssoua",
          categoryAr: "دشيشة",
          wheght: "1kg",
        },
        {
          id: 25,
          nameFr: "Hessoua Marocaine",
          nameAr: "دشيشة درة بلدية غليضة",
          bioFR:
            "La Dashisha de maïs contient une grande proportion de fibres qui aide à se sentir saturé.it est également riche en glucides qui sont importants pour l’énergie de l’organisme.C’est une source riche en fibres, et le maïs est une source riche en vitamine C; C’est un antioxydant qui contribue à maintenir les cellules du corps contre les dommages et à réduire le risque de certaines maladies comme le cancer et les maladies cardiaques",
          bioAr:
            "يحتوي دشيش الذرة على نسبة كبيرة من الألياف التي تساعد على الشعور بالشبع.كما أنها غنية بالكربوهيدرات المهمة لطاقة الجسم.وهي مصدر غنيّ بالألياف، بالإضافة إلى أنّ الذرة تعدّ من المصادر الغنيّة بفيتامين ج؛ وهو أحد مضادات الأكسدة التي تساهم في الحفاظ على خلايا الجسم من التلف، وتقليل خطر الاصابة ببعض الأمراض مثل السرطان وأمراض القلب",
          priceMax: "23",
          priceMin: "21",
          categoryFr: "Hssoua",
          categoryAr: "دشيشة",
          wheght: "1kg",
        },
        {
          id: 26,
          nameFr: "Hessoua de mais Marocaine",
          nameAr: "دشيشة درة بلدية متوسطة",
          bioFR:
            "La Dashisha de maïs contient une grande proportion de fibres qui aide à se sentir saturé.it est également riche en glucides qui sont importants pour l’énergie de l’organisme.C’est une source riche en fibres, et le maïs est une source riche en vitamine C; C’est un antioxydant qui contribue à maintenir les cellules du corps contre les dommages et à réduire le risque de certaines maladies comme le cancer et les maladies cardiaques",
          bioAr:
            "يحتوي دشيش الذرة على نسبة كبيرة من الألياف التي تساعد على الشعور بالشبع.كما أنها غنية بالكربوهيدرات المهمة لطاقة الجسم.وهي مصدر غنيّ بالألياف، بالإضافة إلى أنّ الذرة تعدّ من المصادر الغنيّة بفيتامين ج؛ وهو أحد مضادات الأكسدة التي تساهم في الحفاظ على خلايا الجسم من التلف، وتقليل خطر الاصابة ببعض الأمراض مثل السرطان وأمراض القلب",
          priceMax: "23",
          priceMin: "21",
          categoryFr: "Hssoua",
          categoryAr: "دشيشة",
          wheght: "1kg",
        },
        {
          id: 27,
          nameFr: "Graine de chia",
          nameAr: " بدور الشيا",
          bioFR:
            "Les graines de chia ont été scientifiquement approuvées comme un aliment riche en antioxydants, qui accélère le renouvellement des cellules de la peau, prévient les dommages ou la destruction des cellules, et empêche les graines de chia de montrer des signes d’âge prématuré de la peau causée par l’effet dévastateur.\nLes graines de Chia contiennent un pourcentage élevé de phosphore, qui soutient la croissance des cheveux, et les graines de Chia sont riches en neuf acides aminés nécessaires à la croissance, la santé et la vitalité des cheveux et des ongles. L’ajout de ces graines à la nourriture réduit les tissus adipeux, qui sont un facteur d’obésité, est une excellente source de nourriture pour les enceintes\n",
          bioAr:
            "لقد تم اعتماد بذور الشيا علمياً كمادة غذائية غنية بمضادات الأكسدة.التي تقوم بتسريع تجديد الخلايا في الجلد، وتمنع حدوث تلف أو تدمير للخلايا، كما تمنع بذور الشيا ظهور علامات تقدم سن البشرة المبكرة التي يسببها التأثير المدمر.\nوتحتوى بذور الشيا على نسبة مرتفعة من الفوسفور، والذي يدعم نمو الشعر، كما ان بذور الشيا غنية بتسعة من الاحماض الأمينية الضرورية لنمو وصحة وحيوية الشعر والأظافر. ، كما أن إضافة هذه البذور للطعام تعمل على تقليل الأنسجة الدهنية والتي تعد أحد عوامل السمنة.وتعتبر كذالك مصدرًا غذائيًا ممتازًا للحامل.\n",
          priceMax: "24,5",
          priceMin: "22,05",
          categoryFr: "garine",
          categoryAr: "حبوب",
          wheght: "500g",
        },
        {
          id: 28,
          nameFr: "Graine de quinoa",
          nameAr: "حبوب كينوا",
          bioFR:
            "Les Graine de quinoa aident à réduire la fatigue. Elles sont aussi utiles que l’amincissement des os, car elles contiennent une teneur élevée en calcium, ce qui aide à se protéger contre l’ostéoporose et aide à bien construire les muscles et les os. Il aide également à renforcer le système immunitaire\nParce qu’il y a plusieurs nutriments dans les Graine de quinoa, ils aident à renforcer le système immunitaire, qui protège de l’exposition aux maladies connexes\n\n",
          bioAr:
            "تساعد حبوب الكينوا على التخفيف من الشعور بالتعب والإجهاد.ومفيدة كذالك لتقوية العظام لاحتوائها على نسبة عالية من الكالسيوم، ما يساعد على الحماية من الإصابة بمرض هشاشة العظام، وتساعد على بناء العضلات والعظام بشكل جيد. كما تساعد على تقوية الجهاز المناعي\nلوجود عناصر غذائية متعددة في حبوب الكينوا فإنها تساعد على تقوية الجهاز المناعي، ما يقي من التعرض للأمراض المتعلقة به\n",
          priceMax: "23",
          priceMin: "21",
          categoryFr: "graine",
          categoryAr: "حبوب",
          wheght: "500g",
        },
        {
          id: 29,
          nameFr: "Zemita Marocaine",
          nameAr: "الزميطة المغربية",
          bioFR:
            'La "zometah" est un pilier traditionnel du buffet Ramadan au Maroc, pour ses bienfaits pour la santé d’avoir des ingrédients sains, un mélange de poudre de céréales et d’herbes naturelles qui est mélangé lorsqu’il est utilisé avec du miel ou de l’huile d’olive.\nIl se compose de farine de blé, de lin, de cannelle, alwiza , grain sucré, un peu de sel\n',
          bioAr:
            'تعتبر "الزميطة" من ركائز المائدة الرمضانية التقليدية بالمغرب، لفوائدها الصحية المتمثلة في احتوائها على مكونات صحية،وهي خليط من مسحوق الحبوب والأعشاب الطبيعية تخلط عند الاستهلاك بالعسل أو زيت الزيتون.وتتكون من دقيق القمح ودقيق إلان،زريعة الكتان،القرفة،اللويزة،قزبر،دقيق الشعير،السمسم،حبة حلاوة،النافع،الزعتر،فيلو،الخروب،النبق،وقليل من الملح،"ويمكن طلبها بدون ملح على حسب الطلب',
          priceMax: "45",
          priceMin: "40,5",
          categoryFr: "Zemita",
          categoryAr: "الزميطة",
          wheght: "1kg",
        },
        {
          id: 30,
          nameFr: "Blé beldi Harbel",
          nameAr: "قمح البلدي هربل",
          bioFR:
            "Soupe herbel est l'une des soupes les plus populaires au Maroc\n  elle est fréquemment préparée pendant les vacances et les occasions\nLes grains de blé entier sont une excellente source de vitamines du groupe B, qui aident à augmenter les niveaux d’énergie du corps et à améliorer les fonctions cérébrales.Ils sont également riches en glucides qui en font une excellente source d’énergie dont le corps a besoin pour ses activités quotidiennes.\n",
          bioAr:
            "\nحساء هربل أو حساء القمح المفلق،يعتبر أحد أنواع الشوربات المشهورة في المغرب،ثم انتقل ليصل إلى العديد من الدول العربية، حيث يكثر تحضيره في الأعياد، والمناسبات، ويتميز بكون القمح أحد العناصر الأساسية التي تدخل في تحضيره. تعتبر حبوب القمح الكاملة مصدراً ممتازاً لفيتامينات المجموعة ب، والتي تساعد على زيادة مستويات الطاقة في الجسم وتحسين وظائف الدماغ.كما أنه غني بالكربوهيدرات التي تجعله مصدراً ممتازاً للطاقة التي يحتاجها الجسم لممارسة الأنشطة اليومية\n",
          priceMax: "19",
          priceMin: "17,1",
          categoryFr: "Blé",
          categoryAr: "قمح",
          wheght: "1kg",
        },
        {
          id: 31,
          nameFr: "Blé sans pleur",
          nameAr: "قمح (مفسخ)",
          bioFR:
            'Le blé "non rouille" contient une gamme de nutriments utiles pour le corps, contenant un pourcentage élevé de vitamines, phosphore, minéraux, fer, potassium, sucre, protéines, magnésium, manganèse, zinc, fer, fibres, glucides, acides gras, calcium, et omega.it est utilisé comme un remplacement pour le riz au salade\n\n',
          bioAr:
            'يحتوي القمح المفسخ "بدون قشرة"على مجموعة من العناصر الغذائية المفيدة اللازمة للجسم، حيث يحتوي على نسبة عالية من الفيتامينات، الفوسفور، المعادن، الحديد، البوتاسيوم، السكريات، البروتين، المغنيسيوم، المنغنيز، الزنك، الحديد، الألياف، الكربوهيدرات، الأحماض الدهنية، الكالسيوم، وأوميجا.يستخدم بديلا للأرز في السلطة',
          priceMax: "22",
          priceMin: "19,8",
          categoryFr: "Blé",
          categoryAr: "قمح",
          wheght: "1kg",
        },
        {
          id: 32,
          nameFr: "Farine de lentilles",
          nameAr: "دقيق العدس",
          bioFR:
            "Les lentilles se classent au troisième rang en termes de protéines et d’acides aminés parmi les autres pulses comme les haricots, l’acétysie et d’autres, 26% des calories lentiées par les lentilles à partir de protéines. Un verre de lentilles cuites contenant environ 65% des besoins quotidiens en fibres, et les lentilles aident à réduire l’absorption du sucre dans les intestins et ajuster ses niveaux dans le sang.",
          bioAr:
            "يحتل العدس المرتبة الثالثة من حيث إحتوائه على البروتينات والاحماض الامينية بين القطاني الاخرى كالفول والحمص وغيرها، 26% من السعرات الحرارية التي يمدنا بها العدس مصدرها البروتينات. كوب من العدس المطبوخ يحتوي على ما يقارب 65% من الاحتياج اليومي للألياف،كما تساعد هذه الأخيرة على تقليل امتصاص السكر في الامعاء وضبط مستوياته في الدم.ما يجعله الغذاء المثالي لمرضى السكري",
          priceMax: "22",
          priceMin: "19,8",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "500g",
        },
        {
          id: 33,
          nameFr: "Cofiaa sahraouia",
          nameAr: "كوفيو صحراوية ",
          bioFR:
            "Est un plat intégré car il contient tous les nutriments énergétiques nécessaires au corps humain, le sucre. Le lait et les protéines que nous ajoutons du lait ou de l’eau et peut être adopté chaque matin avec du lait jusqu’à ce qu’ils soient comme la soupe et de boire à tout moment, ils nous donnent les nutriments dont le corps a besoin toute la journée. Ils ont de nombreux avantages sur le ventre, système digestif. Le gain de poids est tout aussi important que cela.\n\n",
          bioAr:
            "الكوفيو الصحراوية طبق متكامل لأنه يحتوي على كل المكونات الغذائية الطاقية التي يحتاجها جسم الانسان، السكريات، الدهنيات والبروتينات سواء أضفنا إليه الحليب أو الماء ويمكننا اعتماده كل صباح مع الحليب حتي تصبح كالحساء ويشرب اي وقت،يمنحنا المكونات الغذائية التي يحتاجها الجسم طوال اليوم.ولها فوائد عدة على المعدة و الجهاز الهضمي ويمكن اخدها و جبة للعشاء. ومن فوئدها كذالك زيادة الوزن",
          priceMax: "28",
          priceMin: "25,2",
          categoryFr: "Farine",
          categoryAr: "دقيق",
          wheght: "900g",
        },
        {
          id: 34,
          nameFr: "Herbes à thé naturelles",
          nameAr: "أعشاب الشاي الطبيعية ",
          bioFR:
            "Les herbes de thé se composent de: philon, ROMARIN, Lavande, Marjolaine, verveine, Salvia, thym, cumin soufi, Basilic, Pelargonium graveolens, temega, Rose et autres herbes , Les avantages de ces herbes naturelles comprennent : Calmer les nerfs et rendre l’homme plus calme, se débarrasser de l’insomnie et la dépression, et aider le système digestif à faire son travail. Ces herbes sont très utiles pour débarrasser le corps de l’excès de poids, enlever l’estomac de la dureté digestive, expulser les gaz et soulager l’abdomen, aider à résister aux tumeurs cancéreuses, et désintégrer les diverses douleurs réparties dans le corps comme les maux de tête, les dents, les coliques et l’abdomen\n \n",
          bioAr:
            "تتكون أعشاب الشاي من :فليو ، أزير ، الخزامی،مردوش،اللويزة،السالمية ، الزعتر ، الكامون الصوفي ،الريحان ،العطرشة ، تيميجة، الورد وأعشاب أخرى ..\nمن فوائد هذه الاعشاب الطبيعية :تهدئة الأعصاب وجعل الإنسان أكثر هدوء،يخلص من الأرق والاكتئاب،كما يساعد الجهاز الهضمي على القيام بأعماله، وتعد هذه الاعشاب مفيدة جدا لتخليص الجسم من الوزن الزائد،يخلص المعدة من عسر الهضم كما يطرد الغازات ويريح البطن،ويساعد على مقاومة الأورام السرطانية،وتسكين الآلام المختلفة والمنتشرة بالجسم كآلام الصداع والأسنان والمغص والبطن\n",
          priceMax: "22",
          priceMin: "19,8",
          categoryFr: "Herbes",
          categoryAr: "أعشاب",
          wheght: "100g",
        },
        {
          id: 35,
          nameFr: "Talbina d'orge",
          nameAr: "تلبينة الشعير",
          bioFR:
            "Talbina se compose de grains d'orge qui contient la peau, et c'est une excellente source de fibres alimentaires, riche en minéraux et en vitamines comme le fer, les vitamines B, le magnésium, le zinc, le phosphore et le cuivre, et il a été démontré que l'orge peut grandement aider à traiter des maladies telles que le diabète, le cancer du côlon, la constipation et les troubles cardiaques. La diverticulose, qui est la plus répandue à cet âge, est l'une des formes les plus courantes de maladies du gros intestin qui peuvent lui nuire gravement. Manger de la talbina peut non seulement l'empêcher de se produire, mais aussi aider le gros intestin à guérir.",
          bioAr:
            "تتكون التلبينة من الحبوب شعير الكاملة التي تحتوي على القشر ، وهي مصدر ممتاز للألياف الغذائية ،الغنية بالمعادن والفيتامينات مثل الحديد وفيتامينات ب والمغنيسيوم والزنك والفوسفور والنحاس ، كما تبين أن الشعير يمكن أن يساعد بشكل كبير في علاج الأمراض مثل مرض السكري وسرطان القولون والإمساك والاضطرابات المرتبطة بالقلب والتي تنتشر في هذا العصر،داء الرتج هي أحد أكثر أشكال أمراض الأمعاء الغليظة شيوعًا والتي يمكن أن تؤذيها بشدة ، أكل التلبينة لا يمكن أن يمنعه من الحدوث فحسب ، بل يساعد الأمعاء الغليظة على الشفاء منه",
          priceMax: "55",
          priceMin: "49,5",
          categoryFr: "farine",
          categoryAr: "دقيق",
          wheght: "900g",
        },
        {
          id: 36,
          nameFr: "Dashisha marocaine",
          nameAr: "الدشيشة المغربية",
          bioFR:
            "La Dashisha marocaine se compose d'orge, de maïs et de blé avec des herbes",
          bioAr:
            "\n  تتكون الدشيشة المغربية من دشيش الشعير والذرة ودشيش القمح بالأعشاب\n",
          priceMax: "24",
          priceMin: "21,6",
          categoryFr: "dchicha",
          categoryAr: "دشيشة",
          wheght: "1kg",
        },
        {
          id: 37,
          nameFr: "Berkoukch marocaine",
          nameAr: "بركوكش مغربي",
          bioFR:
            "Berkoukch est composé de grains de blé naturel, c’est un plat traditionnel amazigh dans tous les pays d’Afrique du Nord, Par tamis, les femmes le transforment en grains circulaires rugueux, laissant sécher au soleil pendant des jours, Il a plusieurs avantages car il contient une combinaison de vitamines et de glucides, qui est une excellente source d’énergie dont le corps a besoin pour ses activités quotidiennes.\n\n",
          bioAr:
            "يتكون بركوكش من حبوب القمح الطبيعي،وهو طبق أمازيغي تقليدي في كل دول شمال افريقيا،تحوله النساء بواسطة الغربال إلى حبيبات دائرية خشنة،ويترك ليجف تحت أشعة الشمس لأيام وربما اسابيع. وله فوائد عدة لاحتوائه على مجموعة من الفيتامينات والكربوهيدرات والتي تعتبر مصدرا ممتاز للطاقة التي يحتاجها الجسم لممارسة الأنشطة اليومية",
          priceMax: "25",
          priceMin: "22,5",
          categoryFr: "berkoukech",
          categoryAr: "بركوكش",
          wheght: "1kg",
        },
      ],
    };
  },
};
</script>
