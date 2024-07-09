<template>
  <div class="bg-red-500 min-h-screen">
    <header class=" text-white p-4">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-8xl font-bold">EURO <br> GAZON</h1>
        <button class="bg-white font-bold text-sm text-green-400 px-8 py-3 rounded-3xl">ЗАКАЗАТЬ ЗВОНОК</button>
      </div>
    </header>

    <main class="container mx-auto p-4">
      <section class="text-left py-10">
        <h2 class="text-xl text-left text-white font-bold mb-4">СТАНЬ ПАРТНЕРОМ ОДНОЙ ИЗ САМЫХ ВЫГОДНЫХ ФРАНШИЗ</h2>
        <p class="text-5xl mb-8">
          <span class="text-white">ПОЛУЧИ ОТ </span>
          <span class="text-green-500">10 000 000₸ <br> ЧИСТОЙ ПРИБЫЛИ В ГОД </span>
          <span class="text-white"><br>С ГАРАНТИЕЙ ПО ДОГОВОРУ</span>
        </p>
        <button class="bg-green-500 text-white px-6 py-3 rounded-3xl">ПОЛУЧТЬ ПЛАН</button>
      </section>
      <section class="text-center py-10  rounded shadow-lg">
        <h3 class="text-3xl text-left font-bold mb-6">
          <span class="text-black">ПРЕИМУЩЕСТВА</span>
          <span class="text-green-500">EURO GAZON:</span>
        </h3>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
          <div class="bg-green-500 text-white p-10 rounded-lg shadow-md relative flex items-left justify-center flex-col text-left">
            <h3 class="text-4xl font-bold">КАЧЕСТВО</h3>
            <p class="mt-2">Быстрый вход <br> в проект до 2-х <br>месяцев!</p>
            <div class="absolute top-0 right-0 w-8 h-8 bg-green-400 rounded-tr-lg"></div>
          </div>
          <div class="bg-green-500 text-white p-10 rounded-lg shadow-md relative flex items-left justify-center flex-col text-left">
            <h4 class="text-4xl font-bold">ВЫГОДА</h4>
            <p>Консультация <br> первых 10 сделок</p>
          </div>
          <div class="bg-green-500 text-white p-10 rounded-lg shadow-md relative flex items-left justify-center flex-col text-left">
            <h4 class="text-4xl font-bold">ГАРАНТИЯ</h4>
            <p> Поставка <br> материалов по <br> выгодным ценам</p>
          </div>
        </div>
      </section>
      <section>
        <div class=" p-8">
          <AchievementsBlock />
        </div>
      </section>
      <section class=" py-5 bg-cover">
        <h2 class="text-4xl font-bold mb-4 text-left">
          <span class="text-white">ЧТО ТАКОЕ ФРАНШИЗА<br></span>
          <span class="text-green-500">EURO GAZON?</span>
          <span class="text-white">?</span>
        </h2>
        <p class="text-xl mb-8 text-left text-white">
          <span class="font-bold">EURO GAZON</span>
          <span class="font-thin text-2xl">— это первая на рынке франшиза простого и <br> выгодного бизнеса по озеленению, благоустройству частных <br> садов, корпоративных территорий, отелей и парков с гарантией <br> прибыли в договоре и круглогодичным доходом.</span>
        </p>
        <form class="flex justify-start text-left ">
          <input type="text" placeholder="Имя" class="p-2 rounded-full mr-2 bg-transparent text-white border border-white">
          <input type="text" placeholder="Телефон" class="p-2 rounded-full mr-2 bg-transparent text-white border border-white">
          <button class="bg-green-500 text-white px-4 py-2 p-2 rounded-full">ЗАПИСАТЬСЯ НА КОНСУЛЬТАЦИЮ</button>
        </form>
      </section>
      <section class="container mx-auto p-8">
        <div class="text-center space-y-6">
          <p class="text-5xl font-bold text-left ">
            <span class=""> КАК ЗАРАБОТАТЬ С НАМИ<br> </span>
            <span class="text-green-400 "> ОТ 10 000 000₸<br> </span>
            <span class=""> С ГАРАНТИЕЙ ПО ДОГОВОРУ </span>
          </p>
          <p class="mb-8 text-left">Ознакомьтесь с видео, как мы вместе заработаем</p>
        </div>
        <div class="flex flex-col md:flex-row items-center justify-between">
          <div class="md:w-2/3 mb-4 md:mb-0">
            <div class="text-center text-2xl font-bold mt-2">Иосиф</div>
          </div>
          <div class="md:w-1/3 bg-green-500 p-6 text-white rounded">
            <h3 class="text-2xl font-bold mb-4">* Важно:</h3>
            <p>Франчайзи партнер — это не специалист в ландшафтном дизайне. Это предприниматель, который ведет бизнес в ландшафтном дизайне, у которого в команде есть профильные специалисты по всем необходимым сферам.</p>
            <p class="mt-4">Наша франшиза про системный и устойчивый бизнес, а не фриланс, самозанятость или курсы по дизайну.</p>
          </div>
        </div>
        <div class=" mt-10">
          <div class="flex-row">
            <img src="/servbay-nuxt-app/assets/images/IOSIF.png" alt="Иосиф" class="h-96">
            <p class="text-2xl  text-green-500 font-bold mb-2 mr-20  ">EURO GAZON<br>
              <span class="text-lg text-zinc-950 mb-4 ">— это бренд, который<br> даст вам возможность<br> заработать.</span>
            </p>
            <p class="text-2xl  text-green-500 font-bold mr-20   mb-2">EURO GAZON<br>
              <span class="text-lg  text-black mr-auto">— выгодное вложение<br> в бизнес для<br> предпринимателей<br> разного уровня.</span>
            </p>
          </div>
        </div>
      </section>
      <section class=" py-10 bg-cover relative" style="background-image: url('/path/to/grass-image.png');">
        <div class="container mx-auto">
          <h2 class="text-4xl mb-4">
            <span class="text-green-500 text-left">ВЫОГДНЫЕ УСЛОВИЯ<br></span>
            <span class="text-white ">ЗАПУСКА ФРАНШИЗЫ</span>
          </h2>
          <p class="text-xl text-white font-thin mb-8">Наша бизнес-модель основана на опыте работы над 900+ проектами.<br> С контрактами от ключевых партнеров. Вы экономите до 45% на ведении бизнеса.</p>
          <p class="text-white text-transform: uppercase mb-20">ПРЕИМУЩЕСТВА бизнес-модели Euro Gazon:</p>
          <div class="grid grid-cols-1 md:grid-cols-3 gap-4 text-white  ">
            <div class="bg-black  bg-opacity-20 rounded-3xl flex items-center">
              <div class="text-9xl font-bold text-green-500  ml-10 mr-20 my-10">1</div>
              <div class="text-white  text-transform: uppercase">
                <p>Продуман<br> каждый шаг в<br> открытии<br> бизнеса, без<br> ошибок и<br> лишних затрат.</p>
              </div>
            </div>
            <div class="bg-black  bg-opacity-20 rounded-3xl flex items-center">
              <div class="text-9xl font-bold text-green-500  ml-10 mr-20 my-10">2</div>
              <div class="text-white text-transform: uppercase">
                <p>Проверенные<br> поставщики<br> посадочного<br> материала и<br> оборудования.</p>
              </div>
            </div>
            <div class="bg-black  bg-opacity-20 rounded-3xl flex items-center">
              <div class="text-9xl font-bold text-green-500  ml-10 mr-20 my-10">3
              </div>
              <div class="text-white text-transform: uppercase">
                <p>Стабильно<br> высокая<br> доходность<br> весь год.</p>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class=" bg-gray-100">
        <div class="container mx-auto">
          <h2 class="text-3xl font-bold mb-6">
            <span class="text-black">О ПРОЕКТЕ<br></span>
            <span class="text-green-400">EURO GAZON</span>
          </h2>
          <div class="grid grid-cols-1 md:grid-cols-4 gap-4">
            <div class="p-4">
              <img src="/servbay-nuxt-app/static/images/icon1.png" alt="Icon 1" class="w-auto h-auto">
              <p>Мы работаем с частными<br> и государственными<br> объектами, облагораживая<br> территории различного<br> масштаба.</p>
            </div>
            <div class="p-4">
              <img src="/servbay-nuxt-app/static/images/icon2.png" alt="Icon 2" class="w-auto h-auto">
              <p>У нас вы сможете заказать<br> комплекс услуг по<br> озеленению – от укладки<br> газона до вертикального<br> озеленения.</p>
            </div>
            <div class="p-4">
              <img src="/servbay-nuxt-app/static/images/icon3.png" alt="Icon 3" class="w-auto h-auto">
              <p>Мы работаем по Алматы<br> и Алматинской области,<br> а иногда за ее пределами.</p>
            </div>
            <div class="p-4">
              <img src="/servbay-nuxt-app/static/images/icon4.png" alt="Icon 4" class="w-auto h-auto">
              <p>Являемся<br> сертифицированным<br> членом Ассоциации<br> Озеленения Казахстана.</p>
            </div>
          </div>
        </div>
      </section>
      <section class="bg-black text-white py-16">
        <div class="container mx-auto">
          <div class=" mb-12">
            <h2 class="text-4xl font-bold mb-4">
              <span class="text-transform: uppercase ">Сколько вы будете</span>
              <span class="text-transform: uppercase text-green-400">зарабатывать</span>
              <span class="text-transform: uppercase">с нами?</span>
            </h2>
          </div>
          <div class="flex flex-col md:flex-row justify-between mr-20 ">
            <div class="mb-6 md:mb-0">
              <p class="text-green-400 text-3xl font-bold text-left">35 000 000₸</p>
              <p class="font-bold mb-5">В МЕСЯЦ</p>
              <p>рекордная прибыль<br> бизнеса в Алматы</p>
            </div>
            <div>
              <p class="text-green-400 text-3xl font-bold">7 000 000₸</p>
              <p class="font-bold mb-5">В МЕСЯЦ</p>
              <p>рекордная прибыль в регионах</p>
            </div>
            <div class="bg-black text-white rounded-lg shadow-md">
              <h3 class="text-green-500 text-xl mb-4">
                <span class="">КЕЙС |</span>
                <span class="text-white">ОТКРЫТИЕ КОМПАНИИ</span>
              </h3>
              <div class=" rounded mb-10">
                <p class="my-5"><strong>ГОРОД</strong> АЛМАТЫ</p>
                <p><strong>НАСЕЛЕНИЕ</strong> 2 500 000 Т</p>
              </div>
              <div class="bg-green-600 p-4 text-center rounded mb-4">
                <strong>СРОК ОКУПАЕМОСТИ: 6 МЕСЯЦЕВ</strong>
              </div>
              <div class="rounded">
                <p class="my-5">ПРИБЫЛЬ<strong>10 000 000 Т</strong></p>
                <p class="my-5">ВЫРУЧКА <strong>50 000 000 Т</strong></p>
                <p class="my-5">ДАТА ОТКРЫТИЯ <strong>1 МАРТА 2023 ГОД</strong></p>
                <p class="my-5">СРЕДНЕЕ КОЛИЧЕСТВО КВАДРАТНЫХ<br> МЕТРОВ В МЕСЯЦ <strong>800 М2</strong></p>
              </div>
            </div>
          </div>
          <div class="flex flex-col md:flex-row justify-between">
            <div class="mb-6 md:mb-0">
              <p class="text-2xl mb-4 font-bold">Рентабельность бизнеса — 45%</p>
              <p class="mb-20 text-transform: uppercase">Средняя выручка проекта партнёров — <b>15 000 000₸</b>><br> средняя прибыль — <b>12 000 000₸</b>></p>
              <form class="flex flex-col">
                <input type="text" placeholder="Имя" class="p-2 mb-4 rounded-full">
                <input type="text" placeholder="Телефон" class="p-2 mb-4 rounded-full">
                <div class="flex items-center mb-4">
                  <input type="checkbox" id="privacy" class="mx-5 border-green-400 bg-black">
                  <label for="privacy" class="text-sm">Я согласен с Политикой конфиденциальности</label>
                </div>
                <button class="bg-green-500 text-white py-2 rounded-full">Получить финансовую модель</button>
              </form>
            </div>
          </div>

          <div class="mt-12">
            <h3 class="text-3xl font-bold mb-6 ">
              <span class="text-white text-5xl text-transform: uppercase ">Опыт</span>
              <span class="text-green-400 text-5xl text-transform: uppercase">франчайзи</span>
            </h3>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>

<script setup>
import AchievementsBlock from '~/components/AchievementsBlock.vue'

</script>

<style scoped>
/* Дополнительные стили для этой страницы */
</style>
