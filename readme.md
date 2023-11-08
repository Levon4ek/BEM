# BEM
head <br>
head__eye_left <br>
head__eye_right <br>
head__nose_big <br>

hair <br>
hair_color_blond <br>
hair_short <br>
hair_clean <br>

body <br>
body__arm_right <br>
body__arm_left <br>
body__stomach_big <br>


legs <br>
legs__length_short <br>
legs__width_big <br>
legs__right_scar_true <br>

# Emmet
## Header

![alt text](./img/1.png)<br>

header.header>nav.header__nav>ul.header__list>(li.header__item>a.header__link>img.header__img)+(li.header__item>a.header__link)*5+(li.header__item>a.header__number)

## Form
![alt text](./img/2.png)<br>

div.repair>(div.repair__wrapper>(h3.repair__title+p.repair__text+form.repair__form>button.repair__button))+img.repair__img

## Card
![alt text](./img/3.png)<br>

section.services>(div.card>img.card__img+h3.card__title+p.card__text)*3

## Review
![alt text](./img/4.png)<br>

div.reviews>(div.reviews__info>(p.reviews__name+u.reviews__date+img.reviews__maps))+(p.reviews__text)+(div.reviews__grade>((u>a.reviews__gray)+img.reviews__stars))