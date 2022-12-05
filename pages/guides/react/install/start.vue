<template>
    <v-row justify="center" align="center">
      <v-col cols="12">
        <v-card>
          <v-sheet class="pa-4">
            <h1>Начало работы</h1>
            <hr class="my-3" />
  
            <div class="mt-6">
              <p>
                На этой странице мы сделаем небольшой обзор документации и других ресурсов, которые могут пригодиться при первом использовании React.
              </p>
              <p><b>React</b> — это JavaScript-библиотека для разработки пользовательского интерфейса.</p>
  
              <div>
                <h2 class="mt-6">Пробуем React</h2>
                <v-divider class="mb-6" />
                <p>
                    React изначально был спроектирован так, чтобы его можно было внедрять постепенно. 
                    Другими словами, <b>вы можете начать с малого и использовать только ту функциональность React, 
                    которая необходима вам в данный момент.</b> Информация в этом разделе будет полезна в любой ситуации: 
                    при первом знакомстве с React, при создании простой динамической HTML-страницы и даже при проектировании 
                    сложного React-приложения.
                </p>
              </div>
  
              <div>
                <h2 class="mt-6">Онлайн-песочницы</h2>
                <v-divider class="mb-6" />
                <p>
                    Если вы просто хотите немного поиграть с React, попробуйте онлайн-песочницу. 
                    Например, вот простейший шаблон на <a href="https://codepen.io/pen?&editors=0010&layout=left">CodePen</a>, 
                    <a href="https://codesandbox.io/s/new">CodeSandbox</a> или <a href="https://stackblitz.com/edit/react-nn5djc">Stackblitz</a>.
                </p>
                <p>
                    Если вы предпочитаете работать в своём редакторе, 
                    <a href="https://raw.githubusercontent.com/reactjs/reactjs.org/main/static/html/single-file-example.html">скачайте тестовый HTML-файл</a>, добавьте 
                    в него код и запустите на своём компьютере. При открытии тестового файла браузер преобразует JSX в обычный код на JavaScript. 
                    Такое преобразование достаточно медленно, поэтому мы рекомендуем использовать этот файл только для простых демонстрационных примеров.
                </p>
              </div>
            </div>
  
            <div>
              <h2 class="mt-6">Добавляем React на сайт</h2>
              <v-divider class="mb-6" />
              <p>
                Вы можете <a href="/guides/react/install/site">добавить React на свой сайт буквально за одну минуту</a>. 
                После этого можно разместить на сайте несколько динамических виджетов 
                и постепенно наращивать использование React в своём проекте.
              </p>
            </div>
  
            <div>
              <h2 class="mt-6">Создаём React-приложение</h2>
              <v-divider class="mb-6" />
              <p>
                Когда вы начинаете проект на React, то <a href="/guides/react/install/site">простая HTML-страница со script-тегами</a> 
                может быть лучшим вариантом. Её можно сделать за минуту.
              </p>
              <p>
                Однако для разработки более развесистого приложения вам, скорее всего, 
                придётся рассмотреть другие варианты настройки рабочего окружения, объединяющие в себе различные технологии. 
                Вот несколько наборов JavaScript-инструментов, которые мы рекомендуем для создания приложения. 
                Каждый из этих инструментов может работать практически без настройки и позволит раскрыть все возможности экосистемы React. 
                <a href="/guides/react/install/app">Подробнее об инструментах</a>.
              </p>
            </div>
  
            <v-btn
              class="mt-6"
              color="success"
              nuxt
              to="/guide/[1.2] introduction"
            >
              Дальше
            </v-btn>
          </v-sheet>
        </v-card>
      </v-col>
    </v-row>
  </template>
  
  <script>
  import SuccessAlert from "~/components/SuccessAlert.vue";
  
  export default {
    name: "GuideInstallation",
    components: { SuccessAlert },
  };
  </script>
  