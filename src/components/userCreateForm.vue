<template>
  <form class="form">
    <div class="field">
      <label for="fam">Фамилия</label>
      <input id="fam" type="text" placeholder="Фамилия" />
    </div>
    <div class="field">
      <label for="name">Имя</label>
      <input id="name" type="text" placeholder="Имя" />
    </div>
    <div class="field">
      <label for="ot">Отчество</label>
      <input id="ot" type="text" placeholder="Отчество" />
    </div>
    <div class="field">
      <label for="birthDate">Дата рождения</label>
      <input id="birthDate" type="date">
    </div>
    <div class="field">
      <label for="phone">Номер телефона</label>
      <input id="phone" type="text" placeholder="+7 (999) 999-99-99" />
    </div>
    <div class="field">
      <label for="sex">Пол</label>
      <input id="sex" type="text" placeholder="Пол" />
    </div>
    <!-- Multiple selection -->
    <div class="field">
      <label for="clientGroup">Группа клиентов</label>
      <select id="clientGroup" multiple>
        <option value="vip">VIP</option>
        <option value="problems">Проблемные</option>
        <option value="oms">ОМС</option>
      </select>
    </div>
    <div class="field">
      <label for="doctor">Лечащий врач</label>
      <select id="doctor">
        <option value="doctor_1">Иванов</option>
        <option value="doctor_2">Захаров</option>
        <option value="doctor_3">Чернышев</option>
      </select>
    </div>
    <div class="field">
      <label for="sms">
        <input type="checkbox" id="sms"> Не отправлять СМС
      </label>
    </div>
    <h2>Адрес</h2>
    <div class="field">
      <label for="index">Индекс</label>
      <input id="index" type="text" placeholder="Индекс" />
    </div>
    <div class="field">
      <label for="country">Страна</label>
      <input id="country" type="text" placeholder="Страна" />
    </div>
    <div class="field">
      <label for="district">Область</label>
      <input id="district" type="text" placeholder="Область" />
    </div>
    <div class="field">
      <label for="city">Город</label>
      <input id="city" type="text" placeholder="Город" />
    </div>
    <div class="field">
      <label for="street">Улица</label>
      <input id="street" type="text" placeholder="Улица" />
    </div>
    <div class="field">
      <label for="house">Дом</label>
      <input id="house" type="text" placeholder="Дом" />
    </div>
    <h2>Паспорт</h2>
    <div class="field">
      <label for="type">Тип документа</label>
      <select id="type">
        <option value="passport">Паспорт</option>
        <option value="birth">Свидетельство о рождении</option>
        <option value="driving">Вод. удостоврение</option>
      </select>
    </div>
    <div class="field">
      <label for="series">Серия</label>
      <input id="series" type="text" placeholder="Серия" />
    </div>
    <div class="field">
      <label for="number">Номер</label>
      <input id="number" type="text" placeholder="Номер" />
    </div>
    <div class="field">
      <label for="whoGive">Кем выдан</label>
      <input id="whoGive" type="text" placeholder="Кем выдан" />
    </div>
    <div class="field">
      <label for="whenGive">Когда выдан</label>
      <input id="whenGive" type="date" placeholder="Когда выдан" />
    </div>
  </form>
</template>

<script>
export default {
  name: "userCreateForm",
};
</script>

<style scoped>
.form {
  width: 90%;
  margin: auto;
}
.field {
  display: flex;
  flex-direction: column;
  margin-bottom: 1rem;
}
</style>
