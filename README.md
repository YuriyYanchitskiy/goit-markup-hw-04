/_ html{ box-sizing: border-box; } _, _::before, _::after{ box-sizing: inherit; } _/ :root { --primary-text-color: #757575; --title-text-color: #212121; --accent-color1: #2196F3; --accent-color2: #FFFFFF; --background-color: #FFFFFF; --other-background-color: #F5F4FA; --background: #2F303A; --blue-background: #2196F3; --items: 3;/_ кількість карток в рядку _/ --indent: 30px;/_ відступи між картками \*/

} /_основний колір фону #FFFFFF_/ /_другорядний колір фону #F5F4FA_/ /_1 колір тексту #757575_/ /_2 колір тексту #212121_/ /_3 колір тексту #2196F3_/ /_4 колір тексту #FFFFFF_/

/_ WebStudio _/

body{ margin: 0px; background-color: #FFFFFF; font-family: 'Roboto', sans-serif; color: #757575; }

.container{ width: 1200px; margin-left: auto; margin-right: auto; /_ padding-left: 15px; padding-right: 15px; _/ outline: 2px solid cyan; }

/_ Логотип хедера _/ .logo-header{ font-weight: 700; font-size: 26px; line-height: 1.19; letter-spacing: 0.03em; color: var(--title-text-color); text-decoration: none; font-family: 'Raleway', sans-serif; /_ display: inline-block; margin: 0px; _/ padding-left: 0; } /_ .container-nav .logo-header{ padding: 0; } _/ .container.header-main{ padding-left: 0px; padding-right: 0; } /_ Посилання _/

/_ Сіра лінія в хедері _/ .header{ border: 1px solid #ECECEC }

/_ Прибирає крапки в списках _/ .list, .lists-a, .lists-b, .lists-c, .lists-d{ list-style: none; padding-left: 0; display: block; }

.list-item:not(:last-child) { margin-bottom: 12px; } .list-item:not(:last-child) { margin-bottom: 12px; } .lists-a, .lists-b, .lists-c{ justify-content: center; align-items: center; width: 1200px; justify-content: space-between; display: flex; }

.list-adress{ list-style: none; padding: 0px; margin: 0px; }

.list, .list-adress{ display: flex; } ul.list{ margin: 0px 0px 0px 93px; padding: 0; } .container-div{ margin-left: auto; }

.header-main, .container-nav{ display: flex; align-items: center; }

.list li:not(:last-child){ margin-right: 50px; }

.list-adress li:not(:last-child){ margin-right: 30px; } .container-nav .studio, .container-nav .portfolio, .container-nav .contacts, .container-div .mail, .container-div .tel{ display: block; padding-top: 32px; padding-bottom: 32px; } .container hero{ margin-left: auto; margin-right: auto; }

/_посилання_/ .studio, .portfolio, .contacts{ font-weight: 500; font-size: 14px; line-height: 1.1; letter-spacing: 0.02em; color: var(--title-text-color); text-decoration: none; display: inline-block; } .list .studio.current, .list .portfolio.current{ color: var(--accent-color1) }

.blue, .studio:focus, .portfolio:focus, .contacts:focus, .mail:focus, .tel:focus, .studio:hover, .portfolio:hover, .contacts:hover, .mail:hover, .tel:hover{ color: var(--accent-color1); } .mail, .tel{ font-weight: 500; font-size: 14px; line-height: 1.1; letter-spacing: 0.02em; color: var(--primary-text-color); text-decoration: none; display: inline-block; }

/_main_/ .hero{ width: 1602px; height: 600px; left: 0px; top: 80px; text-align: center; background: var(--background); /_ margin-left: auto; margin-right: auto; _/ padding: 0;

} .title{ font-weight: 900; font-size: 44px; line-height: 1.4; letter-spacing: 0.06em; text-transform: uppercase; color: var(--accent-color2); display: inline-block;

    margin-top: 0px;
    margin-bottom: 30px;
    display: flex;
    width: 696px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 200px;

}

.button{ color: var(--title-text-color); background-color: var(--background-color); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);

    border-radius: 4px;
    border: none;
    font-weight: 700;
    font-size: 16px;
    line-height: 1.9;
    cursor: pointer;
    display: flex;

} .button.service{ background: var(--blue-background); color: var(--accent-color2); border-color: transparent; display: inline-block; text-transform: none; padding: 10px 32px; text-decoration: none; border-radius: 4px; }

.img1.box, .img2.box, .img3.box{ display: inline-block; } .description { padding-top: 94px; align-items: center; display: flex; }

.title-attention, .title-punctuality, .title-planning, .title-modern{ font-weight: 700; font-size: 14px; line-height: 1.7; letter-spacing: 0.03em; text-transform: uppercase; color: var(--title-text-color); margin-bottom: 10px; margin-top: 30px; width: 270px; } .paragraph-ideological, .paragraph-a-task, .paragraph-equal, .paragraph-significance { font-weight: 400; font-size: 14px; line-height: 1.7; letter-spacing: 0.03em; color: var(--primary-text-color); margin-top: 0px; margin-bottom: 0px; width: 270px; } .doing{ padding-top: 94px; padding-bottom: 94px; }

.title-doing{ font-weight: 700; font-size: 36px; line-height: 1.2; text-align: center; letter-spacing: 0.03em; color: var(--title-text-color); margin-bottom: 50px; margin-top: 0; }

.box{ outline: 2px solid tomato; }

.ourteam{ background: var(--other-background-color); padding-top: 94px; padding-bottom: 94px;

}

.title-team{ font-weight: 700; font-size: 36px; line-height: 1.2; text-align: center; letter-spacing: 0.03em; color: var(--title-text-color); margin-top: 0px; margin-bottom: 50px; }

.igor, .olga, .nicholas, .michael{ background: var(--background-color); box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14), 0px 2px 1px rgba(0, 0, 0, 0.2); border-radius: 0px 0px 4px 4px; } .name, .position{ font-weight: 500; font-size: 16px; line-height: 1.18; text-align: center; letter-spacing: 0.03em; } .name{ margin-top: 30px; margin-bottom: 10px; } .position{ margin-top: 0px; margin-bottom: 16px; }

.igor.box, .olga.box, .nicholas.box, .michael.box{ width: 270px; }

.igor .name, .olga .name, .nicholas .name, .michael .name{ color: var(--title-text-color); } .lists-c{ margin-top: 0px; }

.lists-b{ margin-top: 0px; margin-bottom: 0;

} .lists-d:not(:last-child) { margin-bottom: 9px; }

.footer{ width: 1602px; height: 252px; background: var(--background); margin-left: auto; margin-right: auto;

}

.container.footer{ /_ display: flex; _/ /_ flex-direction: column; _/ /_ align-items: flex-end; _/ padding-top: 60px; padding-bottom: 60px;

} .logo-footer{ font-weight: 700; font-size: 26px; line-height: 1.2; letter-spacing: 0.03em; text-decoration: none; font-family: 'Raleway', sans-serif; margin-left: 201px; /_ padding-top: 60px; _/ margin-bottom: 20px; display: flex; display: inline-block; }

.lists-d{ margin-left: 201px; margin-top: 0; margin-bottom: 0; display: flex; flex-direction: column-reverse;

} /_ .liaddress, .limail{ margin-bottom: 9px; } _/ .white{ color: var(--accent-color2); } .liaddress{ font-weight: 400; font-size: 14px; line-height: 1.7; letter-spacing: 0.03em; text-decoration: none; color: var(--accent-color2); } .liaddress:hover, .liaddress:focus, .limail:hover, .limail:focus, .litel:hover, .litel:focus{ color: var(--accent-color1); }

.limail{ font-weight: 400; font-size: 14px; line-height: 1.7; letter-spacing: 0.03em; text-decoration: none; color: rgba(255, 255, 255, 0.6); }

.litel{ font-weight: 400; font-size: 14px; line-height: 1.7; text-decoration: none; letter-spacing: 0.03em; color: rgba(255, 255, 255, 0.6); }

    /* margin-top: 0px;

} \*/

.address{ font-style: normal }

/_////////////////////////////////////////_/

/_Портфоліо_/

.buttons-portfolio, .icon{ list-style: none; display: flex;  
} .icon {

    flex-wrap: wrap;
    margin: calc(-1 * var(--indent) / 2);
    margin-bottom: 0px;
    margin-top: 50px;
    padding-left: 0;

} .icon .img { display: block; } .buttons-portfolio{ margin: 0px; padding-left: 0; justify-content: center; } .buttons-portfolio .item:not(:last-child){ margin-right: 8px; } /_ .botton-all{ margin-right: 8px; } _/

.options{ padding-top: 94px; padding-bottom: 94px;

}

.button-all, .button-web, .button-applications, .button-design, .button-marketing{ border: none; background: var(--other-background-color); cursor: pointer; color: var(--title-text-color); font-weight: 500; font-size: 16px; line-height: 1.6; letter-spacing: 0.03em; font-family: 'Roboto', sans-serif; display: inline-block; text-transform: none; padding: 6px 22px; text-decoration: none; border-radius: 4px; } .button-all:hover, .button-all:focus, .button-web:hover, .button-web:focus, .button-applications:hover, .button-applications:focus, .button-design:hover, .button-design:focus, .button-marketing:hover, .button-marketing:focus{ background-color: var(--blue-background); border-color: transparent; color: var(--accent-color2); }

.techno, .poster, .seafood, .prime, .boxes, .inspiration, .edition, .lab, .business{ /_ box-sizing: border-box; _/ background: var(--background-color); border: 1px solid #EEEEEE; } .techno-title, .poster-title, .seafood-title, .prime-title, .boxes-title, .inspiration-title, .edition-title, .lab-title, .business-title{ font-weight: 700; font-size: 18px; line-height: 1.9; letter-spacing: 0.06em; color: var(--title-text-color); margin: 20px 24px 4px 24px; } .techno-text, .poster-text, .seafood-text, .prime-text, .boxes-text, .inspiration-text, .edition-text, .lab-text, .business-text{ font-weight: 400; font-size: 16px; line-height: 1.9; letter-spacing: 0.03em; color: var(--primary-text-color); margin: 0px 24px 4px 24px; } /_ ширина ліжок _/ .techno.box, .poster.box, .seafood.box, .prime.box, .boxes.box, .inspiration.box, .edition.box, .lab.box, .business.box{ width: 370px; }

.techno { flex-basis: calc((100% - var(--indent) _ var(--items)) / var(--items)); margin: calc(var(--indent) / 2); } .poster{flex-basis: calc((100% - var(--indent) _ var(--items)) / var(--items)); margin: calc(var(--indent) / 2);

} .seafood{flex-basis: calc((100% - var(--indent) \* var(--items)) / var(--items)); margin: calc(var(--indent) / 2);

} .prime{flex-basis: calc((100% - var(--indent) \* var(--items)) / var(--items)); margin: calc(var(--indent) / 2);

} .boxes{flex-basis: calc((100% - var(--indent) \* var(--items)) / var(--items)); margin: calc(var(--indent) / 2);

} .inspiration{flex-basis: calc((100% - var(--indent) \* var(--items)) / var(--items)); margin: calc(var(--indent) / 2);

} .edition{flex-basis: calc((100% - var(--indent) \* var(--items)) / var(--items)); margin: calc(var(--indent) / 2);

} .lab{flex-basis: calc((100% - var(--indent) \* var(--items)) / var(--items)); margin: calc(var(--indent) / 2);

} .business{flex-basis: calc((100% - var(--indent) \* var(--items)) / var(--items)); margin: calc(var(--indent) / 2);

}
