Network nədir?: Cihazların bir-biri ilə məlumat mübadiləsi apara bilməsi üçün qurulmuş əlaqə sistemidir.

PAN -- (Personal Area Network): Bu şəxsi cihazların kiçik şəbəkəsidir. Adətən 1-10 metr ərazini əhatə edir. Telefon, planşet, laptop kimi cihazları birləşdirir. Əsas texnologiyaları Bluetooth, USB və İnfrared-dir. PAN fərdi istifadə üçündür və böyük şəbəkələrdə tətbiq olunmur.
LAN -- (Local Area Network): Ev, ofis və ya məktəb kimi məhdud bir ərazidəki kompüter və cihazları bir-birinə bağlayan yerli şəbəkədir.
MAN -- (Metropolitan Area Network): Şəhər miqyasında olan şəbəkədir. Bir neçə LAN-ı birləşdirir, adətən bir şəhərin daxilindəki binaları, kampusları əhatə edir.
WAN -- (Wide Area Network): Şəhərlər, ölkələr və hətta qitələr kimi böyük coğrafi əraziləri əhatə edən telekommunikasiya şəbəkəsidir. Bu şəbəkənin əsas məqsədi bir-birindən uzaqda yerləşən LAN-ları birləşdirərək məlumat mübadiləsini təmin etməkdir. Ən böyük WAN nümunəsi İnternetdir.



Network Topologiyaları
Network Topologiyalarının əsas məntiqi şəbəkə qurğularının (cihazların) fiziki və məntiqi olaraq bir-birinə necə qoşulduğunu göstərən strukturdur. Topologiyalar dedikdə 2 növ topologiya var.
Fiziki topologiya: Kabellərin, cihazların real, gözlə görünən düzülüşü (hansı kabel hara gedir, switch hardadır).
Məntiqi topologiya: Məlumatın hansı yolla hərəkət etdiyini göstərir, fiziki düzülüşdən fərqli ola bilər. Məsələn, cihazlar fiziki olaraq ulduz şəklində bağlana bilər, amma məlumat halqa şəklində bir-birindən digərinə ötürülə bilər.

Topologiyalar:
Point to Point topologiyası -- A cihazı ilə B cihazının arasında birbaşa əlaqə qurulmasıdır.
Bus topologiyası -- Bütün cihazlar bir əsas kabelə bağlanır. Bir cihaz mesaj göndərəndə, o bütün xətt boyunca yayılır, hamı görür, amma yalnız ünvanı uyğun olan qəbul edir.
Ring topologiyası -- Hər cihaz növbəti cihaza bağlanır, beləliklə bir dövrə (halqa) yaranır. Məlumat halqa boyunca bir istiqamətdə (və ya ikiqat halqada hər iki istiqamətdə) hərəkət edir, hər cihaz onu növbətiyə ötürür.
Star topologiyası -- Ən çox istifadə olunan topologiyalardan biridir. Burada hər bir cihaz (client) birbaşa router və ya switch-ə bağlıdır. Məlumat ancaq router və ya switch üzərindən ötürülür, digər cihazlara getmir.
Tree topologiyası -- Bir neçə Star topologiyasının iyerarxik şəkildə birləşməsidir. Bir kök (root) cihaz var, ondan budaqlar ayrılır, hər budaqda öz star strukturu olur. Böyütmək asandır (yeni budaq əlavə etmək kifayətdir), amma kök cihaz xarab olarsa bütün şəbəkəyə təsir edir. Adətən böyük şirkətlərdə, hər şöbənin öz alt-şəbəkəsi olub mərkəzə bağlandığı yerlərdə istifadə olunur.
Mesh topologiyası -- Hər cihaz bir neçə (və ya bütün) digər cihazlarla birbaşa bağlanır. Bir bağlantı kəsilsə belə, məlumat alternativ yolla çatdırıla bilər, ona görə çox etibarlıdır. Amma kabel sayı çox olduğu üçün qurmaq və saxlamaq baha və mürəkkəbdir. Adətən kritik infrastrukturda (data mərkəzləri, hərbi şəbəkələr) istifadə olunur.
Hybrid topologiyası -- İki və ya daha çox topologiyanın birləşdirilməsidir (məsələn, bir neçə Star-ın Mesh şəklində bağlanması). Real həyatda əksər müəssisə şəbəkələri Hybrid-dir, çünki hər topologiyanın yaxşı tərəfini birləşdirib zəif tərəflərini azaltmaq olur.




Request və Response nədir?: Misal üçün biz YouTube-a daxil olarkən bizdən request gedir, yəni istək. YouTube-a daxil olduqdan sonra saytın yüklənməsi, videoların görünməsi, logoların görünməsi isə artıq response-dir, yəni cavabdır. Qısaca, request — client tərəfdən olan istəkdir, response isə server tərəfdən olan cavabdır.
