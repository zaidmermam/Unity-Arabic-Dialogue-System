# Unity-Arabic-Dialogue-System
full functioning Arabic Unity Dialogue system 

بالبداية شكرا لتجربتكم نظام الحوارات العربي 
دعني أشرح عمل النظام باختصار 
النظام بعيد على أن يكون كاملا من جميع النواحي و لكنه يقوم بالعمل مع بعض المميزات 


► أولا : كيفية استخدام النظام

هناك سكريبت اسمه dialogue_manager 
يحتوي على array 
و هذا الإرراي يحتوي على جميع الجمل التي تحتاج لعرضها 



► ثانيا : تعابيرالشخصيات 

أولا هناك ميزة عرض الشخصية المتحدثة مع تعبيرها المناسب 
هناك بعض المتغيرات التي يمكنك أن تضيف فوقها ما تشاء مما يجعلك قادرا على إضافة عدد الشخصيات الذي تريده 
هذا يتطلب قراءة سريعة للكود 
و لكن كما في المشروع استخدمت مثال :GN و SN 
G = GERALT , S = SCARLET , N = NORMAL
و هذا المعنى من الأحرف و أنا قمت بإضافتهم أي أن الكريبت لا يعرف معناهم 
بل هو فقط يقوم بمناداة صورة معينة عند قراءة GN 
و الصورة أنا أحددها 
و كذلك لباقي التعابير و هكذا يمكنك أن تضيف العدد الذي تريده من الشخصيات 



► ثالثا : تأثيرات النص

إذا قمت بإضافة حرف الW 
سيتفعل سكريبت للجملة التي أضفت إليها الحرف و هذا السكريبت يجعل النص متعرج (أنيميشن)
و إذا قمت بإضافة حرف الF 
الذي يعبر عن FEAR أي الخوف 
سيقوم أيضا بتفعيل سكريبت يجعل النص متحركا بشكل يعبر عن الخوف 

► رابعا : سرعة الكتابة

هناك متغير يدعى TYPE SPEED 
كلما انخفض كان سرعة الكتابة أسرع لانه يعبر عن الفرق بالثواني بين كل حرف و حرف 
إذا ضغط الاعب على زر "FIRE1" 
أي حرف الZ 
أو حرف الX بالكونرولر 
سيقوم النظام بتسريع الكتابة ثلاثة أضعاف 



► خامسا : شكرا لك

على تجربتك للنظام الذي صنعته 
يمكنك دعمي عن طريق الكلمة الطيبة أو وضع قلب على هذا المشروع بGITHUB 
للتواصل معي على الديسكورد : Kazoya();#9598
و قم بمساعدة المجتمع العربي بتطوير هذا المشروع لجلعه أفضل !
و شكرا 
