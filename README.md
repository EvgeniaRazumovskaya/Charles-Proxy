# 🍶 Charles Proxy 

Используя Charles Proxy, я протестировала <a href="http://demowebshop.tricentis.com/cart"> webshop cart</a>. 

Посмотрите следующие видеоролики, в которых я меняю данные с помощью прокси-сервера для веб-сайта в Google Chrome на <b> ноутбуке Lenovo с ОС Windows </b>: 
<ul>
<li>  <a href="https://drive.google.com/file/d/1RIBkcAnPJFyATiGReKnWBtQuZpIHjnXg/view?usp=sharing">Изменение количества товаров в корзине. </a>   
  Задача - необходимо изменить количество товаров в корзине: в запросе отправляется "2 товара", а возвращаться должно "500". </li> 
<li>  <a href="https://drive.google.com/file/d/1TFx-3_if2mOpQTijA5O_mIiIVCJiEwgK/view?usp=sharing"> Изменение статуса ответа с 200 на 403. </a>  </li> Задача - смоделировать ситуацию, при которой при обращении к сайту сервер вернет статус-код 403.
<li>  <a href="https://drive.google.com/file/d/1Bij82dXoWlaC1e4FwBFC6HwcCW3Z546q/view?usp=sharing">Перенаправление запроса с основного сайта на QA сайт.</a> </li> Задача - перебрасывать запросы с одного окружения на другое. Например, мы не можем проводить прямое тестирование на проде, а должны стучаться к окружению для тестирования. Предположим, что http://demowebshop.tricentis.com/ это продовская версия, а http://demowebshop.tricentis.com/qa это QA стенд. Задача - перенаправить запрос с Prod на QA.
 </ul>

<li>  <a href="https://drive.google.com/file/d/19z64Y9x9mA61iRDniCHL-1nIva5NiPWa/view?usp=sharing"> Удаление товаров из корзины. </li> Задача - необходимо удалить товары из корзины.
<li>  <a href="https://drive.google.com/file/d/1olVD09_OOzeXUXW2gy8iQ1AAj9_00dyR/view?usp=sharing"> Замена сайта картинкой. </a>  Задача - смоделировать ситуацию, при которой при обращении к http://demowebshop.tricentis.com/ пользователь увидит в браузере любую картинку с кошкой
</li> 
