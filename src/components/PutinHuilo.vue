<template>
    <div class="top">
        <div class="top-left">
            <h2 class="top-title">Мапа військових злочинів <span><img src="../assets/ru.png" alt="ru"> Росії</span> проти <span><img src="../assets/ua.png" alt="ua"> України</span></h2>
            <div class="top-text">
                <p>«Ми не атакуємо мирне населення» – говорили вони. Але це лише підступна брехня великої російської пропаганди. Російські війська навмисне спрямовують свої ракетні та авіа удари по мирному населенню, руйнуючи житлові комплекси, дитячі будинки, лікарні, садочки та багато іншого.</p>
                <p>Ми створили інтерактивну карту, яка відкриє очі на правду російського тероризму в Україні.</p>
            </div>
        </div>
        <div class="top-bottom">
            <div class="top-left">
                <h3 class="top-left-title">352 загиблих цивільних <br><span>з них 14 дітей</span></h3>
                <h3 class="top-left-title">1684 поранених <br><span>з них 116 дітей</span></h3>
            </div>
            <div class="top-right">
                <div class="top-right-title">Якщо ви побачили влучення снаряду у цивільні об’єкти або стали свідком загрози життю людей, напишіть нам:</div>
                <a href="mailto:someone@yoursite.com">написати на пошту</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "PutinHuilo"
}
</script>

<style lang="scss" scoped>
.top {
    padding: 70px 80px 100px;
    &-left {
        width: 62.5%;
        flex-shrink: 0;
        &-title {
            font-size: 47px;
            line-height: 43px;
            margin-top: 45px;
            &:first-child {
                margin-top: 0;
            }
            span {
                color: #FF0000;
            }
        }
    }
    &-bottom {
        display: flex;
        margin-top: 80px;
        align-items: flex-end;
    }
    &-right {
        margin-left: 100px;
        background: #F1F1F1;
        padding: 32px 28px;
        display: flex;
        flex-direction: column;
        &-title {
            margin-bottom: 20px;
            font-size: 16px;
            line-height: 19px;
        }
        a {
            font-size: 16px;
            border: 1px solid #000000;
            border-radius: 50px;
            padding: 0 20px;
            line-height: 64px;
            height: 64px;
            text-align: center;
            text-decoration: none;
            color: #000000;
        }
    }
    &-title {
        font-size: 67px;
        line-height: 61px;
        img {
            position: relative;
            top: 8px
        }
        span {
            white-space: nowrap;
        }
    }
    &-text {
        margin-top: 36px;
        p {
            font-size: 20px;
            line-height: 24px;
            margin-top: 24px;
        }
    }
}
</style>
