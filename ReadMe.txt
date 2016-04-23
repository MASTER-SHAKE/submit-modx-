
Changes in css 

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

.required.error {
  border: 1px solid red !important;
  color: red;
}
#success > h2 {
  background: none repeat scroll 0 0 #e31e24;
  color: #fff;
  margin: 0;
  padding: 20px;
  text-align: center;
}
#loading {
  background: none repeat scroll 0 0 #fff;
  padding: 20px;
  width: 300px;
}
#load {
  background: none repeat scroll 0 0 #e31e24;
  height: 10px;
  width: 10%;
}
[name="lastname"]{
  display:none !important;
}
.hidden {
  display:none;
}

////////////////////////////////////////////////////////


<div class="hidden">
    <div id="success">
      <h2>
      Ваша заявка принята!
      <br>
      Мы скоро с Вами свяжемся.
      </h2>
    </div>
    <div id="loading">
      <div id="load"></div>
    </div>
</div>

//////////////////////////////////////////////////////////

name of chunk in modx

@calc_email@
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

<h1>[[+type]]</h1>
<table>
    [[+name:notempty=`<tr>
        <td>Имя:</td>
        <td>[[+name]]</td>
    </tr>`]]
    [[+phone:notempty=`<tr>
        <td>Телефон:</td>
        <td>[[+phone]]</td>
    </tr>`]]
    [[+email:notempty=`<tr>
        <td>E-mail:</td>
        <td>[[+email]]</td>
    </tr>`]]
    [[+message:notempty=`<tr>
        <td>Вопрос:</td>
        <td>[[+message]]</td>
    </tr>`]]
    <tr>
        <td>Сообщение отправленно со страницы:</td>
        <td>[[+url]]</td>
    </tr>
</table>