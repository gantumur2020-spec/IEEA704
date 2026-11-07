LEEA704 — СЕРВЕР ХОЛБОХ (заавал)
================================
Google Sheet «LEEA704_server» (ID 1NSFZKABAmJS-IXslfwvoackyZzN4sMFLVnN-mOg9wHo) ба Apps Script төсөл
https://script.google.com/u/1/home/projects/1Wx55lL9AcsLPVtUtibFfqp_3rQSfVDQgYcJrPz1r3xxeVEEdLb7TI74y/edit
бэлэн болсон (код хадгалагдсан). Үлдсэн алхам:
 1. Төслийг нээж дээд мөрөөс setupOnce функцийг сонгоод ▶ Run → «Review permissions» → өөрийн must.edu.mn
    бүртгэлээр зөвшөөрнө. (Багшийн нууц үг Script Properties-д хадгалагдаж, хуудсууд, БД хавтас үүснэ.)
 2. Кодын эхний setupOnce функцийг (4 мөр) устгаад хадгална.
 3. Deploy → New deployment → Web app → Execute as: Me, Who has access: Anyone → Deploy → URL-ийг хуулна.
 4. index.html доторх  const API_URL = "";  мөрөнд тэр URL-ийг хашилт дотор тавина (эсвэл надад илгээвэл би оруулна).
 5. Оюутны жагсаалтыг вэбийн «Багш → Оюутны дүн → Жагсаалт оруулах»-аар эсвэл LEEA704_Оюутан хуудсанд шууд оруулна.

LEEA704 «Цахилгаан системийн тооцооны алгоритм, программчлал» (3 кр) — хичээлийн вэб (EEA709-ийн загвар, Номин өнгө)
Хаяг: https://gantumur2020-spec.github.io/ILEEA704/

GitHub-д: шинэ ILEEA704 repository үүсгэж (Settings → Pages → main), энэ архивын бүх файлыг хавтсаар нь нэг дор оруулна.

Агуулга:
  index.html — вэб (лекц 12, тест 120, бодлогын дасгал 180, семинар 12, бие даалт 6 жишээ бодолттой, лаборатори 6 виртуал стенд,
               хичээлийн стандарт, хуваарь, багшийн тухай, зочин горим, оюутны жагсаалт засах)
  pdf/lec01–12.pdf — лекцүүд;  tts/ — лекцийг уншиж сонсгох өгөгдөл
  docs/ — хөтөлбөр, 120 тест, бие даалт (PDF, Word), лаборатори, семинар (Word)
  Code.gs — Google Apps Script серверийн код (нууц үггүй)

СЕРВЕР: Google Sheet «LEEA704 Цахилгаан системийн тооцооны алгоритм, программчлал — оноо» (gantumur2020@must.edu.mn)
хуудсууд: LEEA704_Оюутан (24 оюутан: ДаТС 14 + ЭХИС 10), LEEA704_Log, LEEA704_БиеДаалт, LEEA704_НэгдсэнДүн.
Apps Script нийтлэгдсэн (Anyone); index.html-ийн API_URL энэ серверт холбогдсон. Багшийн нууц үг зөвхөн Script Properties-д.
