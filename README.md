# Metasploit-Arabic


Metasploit

الإطار الخاص بـ Metasploit هو أداة قوية للغاية تخدم على حد سواء المجرمين السيبرانيين والمهاجمين الأخلاقيين في استكشاف وفحص الثغرات في الشبكات والخوادم. نظرًا لطبيعتها مفتوحة المصدر ، يمكن تخصيصها واستخدامها بسهولة على مختلف أنظمة التشغيل.

يمكّن Metasploit فرق اختبار الاختراق من استخدام رموز موجودة مسبقًا أو شخصية لتقييم الشبكات والبحث عن الثغرات المحتملة. تشمل هذه الممارسة ، التي تشبه صيد التهديدات ، تحديد ووثق الضعف ، مما يمكّن تنفيذ حلول مستهدفة وتحديد أولويات تحسينات النظام.

بدأ مشروع Metasploit في عام 2003، وقام H.D. Moore بتأسيسه بهدف إنشاء أداة محمولة للشبكات باستخدام لغة Perl. قدم مطور النواة Matt Miller المساعدة خلال مراحل المشروع الأولى. بحلول عام 2007، تم تحويل المشروع بأكمله إلى لغة Ruby، وفي عام 2009، حصلت Rapid7 على ترخيص المشروع. منذ ذلك الحين، أصبح Metasploit جزءًا أساسيًا من مجموعة أدوات Rapid7، التي تشمل تطوير توقيعات نظام الكشف عن التسلل (IDS)، واستغلال الثغرات عن بُعد المستهدف، وتقنية fuzzing، وأدوات مكافحة الأدلة الجنائية، وأدوات التهرب.

تم دمج مكونات مختلفة من هذه الأدوات في إطار Metasploit، والذي يتم دمجه في نظام التشغيل Kali Linux. بالإضافة إلى ذلك، قامت Rapid7 بتطوير أداتين مملوكتين بشكل خاص وهما Metasploit Pro و Metasploit Express.

أصبح هذا الإطار هو الخيار المفضل لتطوير الاستغلال والتخفيف. قبل Metasploit، كان على فرق اختبار الاختراق أن يقوموا يدويًا بجميع الاختبارات باستخدام مجموعة من الأدوات التي قد تدعم أو قد لا تدعم النظام الذي يتم اختباره. كما كان عليهم كتابة الشفرة الخاصة بهم يدويًا وإدخالها يدويًا إلى الشبكات. كان اختبار التجربة عن بُعد نادرًا، مما يحد من قدرة أخصائيي الأمان على الوصول إلى مناطق محلية أو يتطلب من الشركات استثمار مبالغ كبيرة في خدمات تكنولوجيا المعلومات أو استشاريي الأمان الداخليين.




تستخدم Metasploit، مع مجموعة تطبيقاته الواسعة وتوفره كمصدر مفتوح، من قبل مختلف الأفراد، بدءًا من المحترفين في مجال DevSecOps النامي وحتى القراصنة. يُثبت كونه مفيدًا لأي شخص يبحث عن أداة يمكن تثبيتها بسهولة وتعتمد عليها لإنجاز المهمة المطلوبة، بغض النظر عن المنصة أو لغة البرمجة المستخدمة. شهرة البرنامج بين القراصنة وتوافره الواسع يؤكد على أهمية أن يتعرف أخصائيو الأمان على الإطار، حتى لو لم يستخدموه بشكل فعال.

يتضمن Metasploit الآن مجموعة تبلغ أكثر من 1677 استغلالًا مُنظمة عبر 25 منصة، بما في ذلك Android وPHP وPython وJava وCisco وغيرها. علاوة على ذلك، يوفر الإطار ما يقرب من 500 حمولة، تشمل:

•	حمولات واجهة الأوامر التي تمكن المستخدمين من تنفيذ سيناريوهات أو أوامر عشوائية على الجهاز المستضيف.

•	حمولات ديناميكية تسمح لمختبري الاختراق بتوليد حمولات فريدة للتهرب من برامج مكافحة الفيروسات.

•	حمولات Meterpreter التي تمنح المستخدمين السيطرة على مراقبي الأجهزة من خلال VMC، مما يتيح استيلاء الجلسة وتحميل وتنزيل الملفات وما إلى ذلك.

•	حمولات ثابتة تسهل إعادة توجيه المنفذ والاتصال بين الشبكات.

كيفية الحصول على Metasploit

يتوفر Metasploit عبر مثبتات مصدر مفتوح مباشرة من موقع Rapid7. بالإضافة إلى أحدث إصدار من متصفحات Chrome أو Firefox أو Explorer، فإن متطلبات النظام الدنيا هي:


Ubuntu Linux 14.04 or 16.04 LTS (recommended)
Windows Server 2008 or 2012 R2
Windows 7 SP1+, 8.1, or 10
Red Hat Enterprise Linux Server 5.10, 6.5, 7.1, or later


