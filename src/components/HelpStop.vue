<template>
    <div class="stop">
        <div class="stop-content">
            <h2 class="stop-title">Як ви можете<br/> допомогти <span>це<br/> зупинити</span></h2>
            <ul class="stop-list">
                <li class="stop-list-item">
                    <h5>
                        1. Читайте <span>перевірені</span> джерела
                    </h5>
                    <div class="stop-list-flex">
                        <div class="stop-list-flex-item">
                            <p>ЗМІ для україномовних друзів:</p>
                            <a href="https://www.ukrinform.ua/" target="_blank">ukrinform.ua</a>
                        </div>
                        <div class="stop-list-flex-item">
                            <p>ЗМІ для іноземних друзів:</p>
                            <a href="https://kyivindependent.com/" target="_blank">Kyiv independent</a>
                            <a href="https://ukrainer.net/" target="_blank">ukrainer</a>
                        </div>
                    </div>
                </li>
                <li class="stop-list-item">
                    <h5>
                        2. <span>Поширюйте</span> правду,<br/> світ має знати
                    </h5>
                    <div class="stop-list-text">
                        <p>Діліться цим сайтом у своїх соцмережах. Надсилайте друзям та рідним.</p>
                        <p>Розповідайте про події в Україні, особливо людям з Росії та Білорусі. Переконуйте тих, хто вважає, що Україна сама попросила Росію про «визволення». Це ганебна брехня, яка коштує життя мирного населення.</p>
                    </div>
                </li>
                <li class="stop-list-item">
                    <h5>
                        3. Виходьте на антивоєнні <span>мітинги</span> у своїх містах та підтримуйте Мир. Об’єднуйтесь щоб бути почутими.
                    </h5>
                </li>
                <li class="stop-list-item">
                    <h5>
                        4. <span>Допомагайте</span> українцям тут і зараз:
                        <div class="stop-list-text">
                            <a href="">Фонд Національного Банку України”</a>
                            <a href="">Фонд “Повернись живим”</a>
                        </div>
                    </h5>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: "HelpStop"
}
</script>

<style lang="scss" scoped>
.stop {
    padding: 70px 80px 100px;
    background: #000000;
    &-title {
        color: #ffffff;
        font-size: 67px;
        line-height: 61px;
        span {
            color: #FF0000;
        }
    }
    &-title {
        width: 100%;
    }
    &-content {
        display: flex;
        flex-direction: column;
        align-items: flex-end;
    }
    &-list {
        width: 60%;
        margin-top: 50px;
        &-item {
            margin-bottom: 70px;
            &:last-child {
                margin-bottom: 0;
            }
        }
        h5 {
            font-size: 37px;
            line-height: 44px;
            color: #ffffff;
            span {
                color: #FF0000;
            }
        }
        p, a {
            color: #ffffff;
            font-size: 16px;
            line-height: 21px;
        }
        a {
            text-decoration: underline;
            margin-top: 16px;
        }
        p {
            margin-top: 16px;
            &:first-child {
                margin-top: 0;
            }
        }
        &-flex {
            margin-top: 36px;
            display: flex;
            justify-content: space-between;
            &-item {
                width: calc(50% - 42px);
                display: flex;
                flex-direction: column;
                justify-content: space-between;
            }
        }
        &-text {
            margin-top: 28px;
        }
    }
}
</style>
