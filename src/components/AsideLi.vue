<script setup>
import MainItem from './MainItem.vue';

</script>

<template>
     <ul class="aside-items">
          <li><a href="/" class="aside-item"> <img src="/src/components/dashboard_icons/menu.svg" alt="menu">
                    <p class="li-text">Data Table</p><span class="li-btn-list"><img
                              src="/src/components/dashboard_icons/menu-_1_.svg" alt="menu list"></span>
               </a></li>
          <li><button class="aside-item"><img src="/src/components/dashboard_icons/kanban.svg" alt="kanban">
                    <p class="li-text">Kanban</p><span class="li-btn-list"><img
                              src="/src/components/dashboard_icons/menu-_1_.svg" alt="menu list"></span>
               </button></li>
          <div class="tabs"> <input type="radio" name="tab-btn" id="tab-btn-1" value="" checked>
               <label for="tab-btn-1" class="aside-item"><img src="/src/components/dashboard_icons/diagram.svg"
                         alt="diagram">
                    <p class="li-text">Analytics</p> <span class="li-btn-list"><img
                              src="/src/components/dashboard_icons/menu-_1_.svg" alt="menu list"></span>
               </label>

          </div>

          <li><button class="aside-item"> <img src="/src/components/dashboard_icons/image2vector.svg" alt="document">
                    <p class="li-text">Project Manager</p><span class="li-btn-list"><img
                              src="/src/components/dashboard_icons/menu-_1_.svg" alt="menu list"></span>
               </button></li>
          <li><button class="aside-item"> <img src="/src/components/dashboard_icons/calendar.svg" alt="calendar">
                    <p class="li-text">Calendar</p><span class="li-btn-list"><img
                              src="/src/components/dashboard_icons/menu-_1_.svg" alt="menu list"></span>
               </button></li>
          <li><button class="aside-item"> <img src="/src/components/dashboard_icons/shopingcart.svg" alt="shopingcart">
                    <p class="li-text">Ecommerce</p><span class="li-btn-list"><img
                              src="/src/components/dashboard_icons/menu-_1_.svg" alt="menu list"></span>
               </button></li>
     </ul>

     <div class="tabs">
          <input type="radio" name="tab-btn" id="tab-btn-1" value="" checked>
          <label for="tab-btn-1">Вкладка 1</label>
          <input type="radio" name="tab-btn" id="tab-btn-2" value="">
          <label for="tab-btn-2">Вкладка 2</label>
          <input type="radio" name="tab-btn" id="tab-btn-3" value="">
          <label for="tab-btn-3">Вкладка 3</label>


          <div id="content-2">
               Содержимое 2...
          </div>
          <div id="content-3">
               Содержимое 3...
          </div>
     </div>

</template>

<style>
.tabs {
     max-width: 350px;
     margin-left: auto;
     margin-right: auto;
}

.tabs>input[type="radio"] {
     display: none;
}

.tabs>input[type="radio"]:checked+label {
     background: rgba(252, 165, 73, 0.08);


}

.tabs>div {
     /* скрыть контент по умолчанию */
     display: none;
     border: 1px solid #eee;
     padding: 10px 15px;
     border-radius: 4px;
}

/* отобразить контент, связанный с вабранной радиокнопкой (input type="radio") */
#tab-btn-1:checked~#content-1,
#tab-btn-2:checked~#content-2,
#tab-btn-3:checked~#content-3 {
     display: block;
}

.tabs>label {
     text-align: center;
     vertical-align: middle;
     user-select: none;

     border: 1px solid transparent;
     font-size: 16px;
     line-height: 1.5;
     border-radius: 4px;
     transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out;
     cursor: pointer;
}
</style>

