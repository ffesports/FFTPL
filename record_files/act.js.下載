$(document).ready(function () {

    $(" .arrowmove").click(function (evn) {
        var cc = $("#header").height();
        $("body,html").animate({
            scrollTop: cc - 30
        }, 1600);
    });


});



//漢堡MenuJS
$('.burger, .overlay').click(function () {
    $('.burger').toggleClass('clicked');
    $('.overlay').toggleClass('show');
    $('nav.navmobile').toggleClass('show');
    $('body').toggleClass('overflow');
});
$('nav.navmobile li').click(function () {
    $('.burger').toggleClass('clicked');
    $('.overlay').toggleClass('show');
    $('nav.navmobile').toggleClass('show');
    $('body').toggleClass('overflow');
});

     //注意事項JS
        $('.warnbox .title ').on('click', function () {
            $(this).children('.circle-plus').toggleClass('opened');
            $(this).parent().children('ul').toggleClass('opened');
        })