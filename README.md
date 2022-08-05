# goit-markup-hw-01
       <form class="modal-form">
        <p class="modal-text">Залиште свої дані, ми вам передзвонимо</p>
        <label class="modal-form-field">
          <span class="modal-form-input-desc">Ім'я</span>
          <span class="modal-form-input-wrapper">
            <svg class="modal-form-input-icon" width="18" height="18">
              <use href="./images/symbol-defs.svg#icon-instagram"></use>
            </svg>
          <input
          type="text"
          name="user_name"
          class="modal-form-input"
          required
          pattern="[a-zA-Zа-яА-Я]+"
          minlength="2"
        />        
        </span>
      </label>

        <label class="modal-form-field">
          <span class="modal-form-input-desc"> Телефон </span>
          <span class="modal-form-input-wrapper">
            <svg class="modal-form-input-icon" width="18" height="18">
              <use href="./icons.svg#icon-phone"></use>
            </svg>
            <input
              type="tel"
              name="user_phone"
              class="modal-form-input"
              required
              pattern="[0-9]{3}-[0-9]{3}-[0-9]{2}-[0-9]{2}"
              title="xxx-xxx-xx-xx"
            />
            </span>
            </label>

        <label class="modal-form-field">
          <span class="modal-form-input-desc">Пошта</span> 
          <span class="modal-form-input-wrapper">         
            <svg class="modal-form-input-icon" width="18" height="18">
              <use href="./icons.svg#icon-mail"></use>
            </svg>
          <input
          type="email"
          name="user_name"
          class="modal-form-input"
          required
          pattern="[a-zA-Zа-яА-Я]+"
          minlength="2"> 
          </span>  
        </label>

        <label class="modal-form-field">
          <span class="modal-form-input-desc">Коментар</span>

          <textarea name="user_massege" class="modal-form-message" placeholder="Введіть текст"></textarea>
        </label>

        <input
        id="user-policy"
        type="checkbox"
        name="user_policy"
        class="modal-form-check visually-hidden"
      />        
      <label for="user-policy" class="modal-form-check-desc">Погоджуюся з розсилкою та приймаю&nbsp; <a href="">Умови договору</a></label>
        <button type="submit" class="modal-form-submit">Відправити</button>
      </form>







                    <input
              id="user-policy"
              type="checkbox"
              name="user_policy"
              class="modal-form-check visually-hidden"
            />        
            <label for="user-policy" class="modal-form-check-desc">Погоджуюся з розсилкою та приймаю&nbsp; <a href="">Умови договору</a></label>