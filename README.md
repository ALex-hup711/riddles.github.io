
<script>
    var res_true= 0;
    var res_false=0;
    alert("Давай поиграем")
    alert("Попробуй отгадать 3 загадки");
    alert("Готов? - Поехали")
    alert("Первая загадка");
    
    var name1=prompt("Сколько будет = 2+2*2 ?");
    if(name1=="6") {
    alert("Молодец!");
       res_true=res_true+1;
    } else { alert("Увы, неверно..");
       res_false=res_false+1;
    }
    
    alert("вторая загадка");
    var name2=prompt("Сколько пальцев у человека?");
    if(name2=="20") {
    alert("Верный ответ!");
        res_true=res_true+1;
    } else { alert("Неверно! Похоже, что ты ошибся..");
        res_false=res_false+1;
    }
    
    alert("третья загадка");
    var name3=prompt("На раскрашенных страницах Много праздников хранится.");
    if(name3=="Календарь") {
    alert("Молодец");
        res_true=res_true+1;
    } else { alert("неверно :)");
        res_false=res_false+1;
    }
    alert("Чтож, посмотрим на твои результаты")
    
    alert("Правильных ответов :" + res_true);
    
    if(res_true==3){
        alert("3/3 - Молодец, так держать");
    }
    if(res_true==2){
        alert("2/3 - Неплохо. В следующий раз будет лучше");
    }
    
    if(res_true==1){
        alert("1/3 - 1 правильный ответ это уже что то)");
    }
    
    if(res_true==0) {
         alert("0/3 - Чтож, любой результат тоже результат. Увы, ты проиграл, так как не угадал ни одной загадки.");
    }
    alert("Спасибо и до новых встреч");
    alert("КОНЕЦ игры");
</script>
