# git-projekt-Andy_Pepa_Anca
Malý git projekt
Popis projektu: Jednoduchá webová stránka 
Autoři: Andrea Semančinová, Anna Spieglová, Josef Šubrt
Návod k použití: Používá se jako každá jiná webová stránka. Stáhněte si html a hoďte na hosting nebo localhost.
Rozdělení úkolů: Pepa - programátor, Andy - tester/bug fixer, Anča - grafik
Ukázka: document.querySelectorAll('a[href^="#"]').forEach(a=>{
            a.addEventListener('click', e=>{
                const id = a.getAttribute('href').slice(1);
                const el = document.getElementById(id);
                if(el){ e.preventDefault(); el.scrollIntoView({behavior:'smooth',block:'start'}); }
            })
        });
