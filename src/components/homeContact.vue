<template>
    <div class="wrapper">
        <div class="container">
            <h1>Contact</h1>
            <div class="formButton">
                <p class="discriptionButton">
                    <router-link to="/Contact">お問い合わせフォーム</router-link>
                </p>
            </div>
            <p style="font-size: 22px;">or</p>
            <p style="font-size: 22px;">email: hobirondokidoki5150[@]gmail.com</p>
        </div>
    </div>
</template>


<style lang="scss" scoped>

$home: #F47C00;

.wrapper{
    margin-top: 80px;
}


.container{
    padding-top: 30px;
    padding-bottom: 10px;
    text-align: center;
    margin: 0 auto;
    background-color: rgb(252, 252, 252);;

    h1{
        font-weight: bold;
    }

    .discriptionButton {

        a {
            margin: 0 auto;
            display: block;
            padding: 14px 20px;
            margin-top: 10px;
            width: 200px;
            font-weight: bold;
            font-size: 20px;
            border: solid 2px $home;
            text-align: center;
            transition: all 0.3s;
            color: $home;
            text-decoration: none;
            &:hover {
                background-color: $home;
                color: white;
            }
        }
    }
}
</style>