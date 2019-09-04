# Untitled

@import 'samsung-foundation'; @import 'global';

@media screen and \(max-width: 768px\) { .serviceLandingHead { width: auto !important; font-size: 40px !important; margin: 40px auto !important; } .serviceLandingThreeColumns { margin: 0 !important; .shareColumns { .columnKid { width: 361px !important; height: 259px !important; margin-left: 29px !important; float: left !important;

```text
            .service-description {
                text-align: center !important;
                margin-left: 10px !important;
                margin-right: 10px !important;

                .product-name {
                    font-size: 17px !important;
                    height: 17px !important;
                }

                .product-description {
                    font-size: 15px !important;
                    width: 335px !important;
                }
            }
        }

        .corouselInside {
            margin-top: 10px;
        }

    }
}
```

}

@media screen and \(min-width: 769px\) {

} .serviceLandingHead { width: 1440px; height: 68px; font-family: SamsungSharpSans; font-size: 67px; font-weight: bold; font-style: normal; font-stretch: normal; line-height: 1.01; letter-spacing: normal; text-align: center; color: \#000000; margin: 72px auto;

}

.serviceLandingThreeColumns { clear: both; position: relative; max-width: 1440px; margin: 0 132px; //background-color: \#f6f6f6; .columnWrapper { width: 401px; overflow: hidden; //position: relative; .shareColumns { display: flex; width: 1440px; height: 400px; transition: all 2s;

```text
        .columnKid {
            width: 399px;
            height: 259px;
            margin-left: 10px;
            margin-right: 10px;
            float: left;
            .columnKid_img {
                object-fit: cover;
                object-position: top;
                width: inherit;
                height: 259px
            }
            .corouselInside {
                //display: none;
                .shareCorousel {
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    li {
                        position: relative;
                        display: inline-block;
                        height: 20px;
                        width: 20px;
                        margin: 0 5px;
                        padding: 5px;
                        cursor: pointer;
                    }

                    button {
                        border: 1px solid #000;
                        -webkit-border-radius: 50%;
                        border-radius: 50%;
                        background: transparent;
                        display: block;
                        height: 10px;
                        width: 10px;
                        outline: none;
                        line-height: 0;
                        font-size: 0;
                        color: transparent;
                        padding: 0;
                        cursor: pointer;


                    }
                    .serviceActived {
                            background-color: #000;
                    }

                }
            }

            .service-description {
                .product-name {
                  width: 288px;
                  height: 31px;
                  font-family: SamsungSharpSans;
                  font-size: 28px;
                  font-weight: bold;
                  font-style: normal;
                  font-stretch: normal;
                  line-height: normal;
                  letter-spacing: 1.38px;
                  text-align: center;
                  margin-top: 28px;
                  margin-bottom: 10px;
                  margin-left: 44px;
                  margin-right: 44px;
                  color: #000000;
                }

                .product-description {
                  width: 355px;
                  height: 59px;
                  font-family: SamsungOneLatinWeb;
                  font-size: 14px;
                  font-weight: normal;
                  font-style: normal;
                  font-stretch: normal;
                  line-height: 1.43;
                  letter-spacing: normal;
                  text-align: center;
                  margin-left: 10px;
                  margin-right: 10px;
                  color: #000000;
                }
            }
        }
    }
}; 
```

} .modelPickerContainer { clear: both; position: relative; max-width: 1440px; margin: auto; //background-color: \#f6f6f6; @include lg { padding: 11px 0px 80px 0px;  
} @include sm { padding: 50px 0px;  
} & a:focus{ outline-color: \#4d90fe; outline-style: solid; outline-width: thin; } .modelPicker{ &List { @include sm{ display: none !important; } } &ContentTitle { height: 17px; } &Content{ margin-bottom: 20px; & ul{ & li{ cursor: pointer; display: inline-block; text-align: center; vertical-align: top; border: solid 1px \#e0e0e0; background-color: \#ffffff; border-image: initial; transition: all 0.2s ease; @include lg{ margin: 0px 18px 18px 0px;  
width: 175px; height: 190px; } @include sm{ margin: auto 7px; margin-bottom: 14px; width: 130px; height: 100px; } & a{ width: 100%; height: 100%; padding: 0; display: flex; flex-direction: column; justify-content: center; } &:hover { opacity: 1; transform: scale\(1.02\); } } } & h5{ color: \#000000; line-height: normal; letter-spacing: 0.2px; font-family: SamsungOneLatinWeb; font-weight: bold; text-align: center; @include lg{ font-size: 14px;  
margin-top: 18px; } @include sm{ font-size: 11px;  
/_margin-top: 5px;_/ } } } &NoHover { pointer-events: none; border-style: none !important; } &Header { position: relative; margin: 0 20px; } &HeaderNav { display: inline-block; position: absolute; top: 58px; left: 0; padding-left: 32px; text-align: left; font-weight: 400; z-index: 101; & \#previous:before { content: "\E903"; display: inline-block; font-family: SamsungSharpGraphic!important; font-size: 26px; color: \#000; position: absolute; left: -3px; top: 6px; cursor: pointer; } .navList { display: inline; &Single { display: block; font-size: 18px; color: \#000; text-transform: capitalize; font-weight: bold; max-width: 160px; cursor: pointer; margin-top: 12px; } &MulTop { font-size: 12px; color: \#9b9b9b; cursor: pointer; font-weight: bold; } &MulLow { display: block; font-size: 18px; color: \#000; text-transform: capitalize; font-weight: bold; max-width: 200px; cursor: pointer; margin-top: 8px; } &Arrow:after { content: "\E902"; font-weight: 700; font-size: 8px; color: \#9b9b9b; font-family: SamsungSharpGraphic!important; padding: 4px; } } } &Fadeout { opacity: 0.4; } }

```text
.modelPickerContent ul, .servicePicker ul {
    text-align: center;
    margin: 0px auto;
    list-style: none;
}

.modelPickerContentImage img {
    @include lg{
        height: 84px;
    }
    @include sm{
        height: 39px;
    }
}

.servicePickerContentImage img {
    @include lg{
        height: 84px;
    }
    @include sm{
        height: 75px;
    }
}

.cta-button {
    background-color: #1428a0;
    color: #ffffff;
    font-size: 11px;
    letter-spacing: 2.2px;
    @include lg{
        width: 290px;
    }
    @include sm{
        width: 200px;
    }
}

.ctaContinue {
    pointer-events: none;
    position: inherit !important;
}

.goToMyProducts:hover {
    background-color: #1428a0;
}

.loginLink {
    width: 50px;
    color: #000000;
    line-height: 9px;
    margin-top: 10px;
    border: none;
    padding: 10px 0px;
    border-bottom: 1px solid #1428a0;
    -webkit-border-radius: 0px;
    border-radius: 0px;
    background-color: transparent;
    &Anchor {
        @include lg{
            margin-left: 45px;                
        }
        @include sm {
            margin-left: 20px;
        }
    }
    &:hover {
        font-size: 11.5px;
        color: #000000 !important;
        background-color: transparent !important;
        border-color: #000000 !important;
    }
}

.upperTitle {
    min-height: 64px;
    font-family: SamsungOneLatinWeb;
    font-weight: bold;
    letter-spacing: normal;
    padding-bottom: 34px;
    padding-top: 65px;
    text-align: center;
    color: #000000;
    @include lg{
        line-height: 1;
        font-size: 24px;
        margin: 0 20px;        
    }
    @include sm{
        font-size: 18px;
        margin: 0 45px;
    }
}

.lowerButton {
    width: 35%;
    margin: auto;
    display: flex;
    justify-content: center;
}

.lastLeaf {
    @include lg {
        font-size: 15px !important;
        transform: translateY(-100%);
    }
    @include sm {
        font-size: 11px !important;
        margin-top: 20% !important;
        transform: translateY(-100%);
    }
}

.locationRed {
    color: red;
    font-weight: bold !important;
}

.servicePicker {
    & ul li {
        cursor: pointer;
        text-align: center;
        vertical-align: top;
        border-width: 1px;
        border-style: solid;
        border-color: rgb(210, 210, 210);
        border-image: initial;
        transition: all 0.2s ease;
        position: relative;
        @include lg{
            width: 285px;
            display: inline-block;
            margin: 0px 25px 35px 0px;       
        }
        @include sm{
            display: block;
            width: 285px;
            left: 50%;
            transform: translateX(-50%);
            margin: 0px 0px 25px 0px;       
        }
        & a {
            width: 100%;
            height: 100%;
            padding: 19px;
        }
    }
    &Title {
        font-size: 14px;
        font-weight: 700;
        color: rgb(0, 0, 0);
        line-height: 1.4;
        font-family: 'SamsungSansSharp';
        letter-spacing: 3px;
        padding: 10px;
    }
    &ContentTitle{
        @include lg {
            font-size: 21px;
            padding-top: 15px;
        }
        @include sm {
            font-size: 14px;
            padding-top: 15px;
            padding-bottom: 24px;
        }            
    }
    &Content {
        font-size: 12px;
        font-weight: unset;
        font-family: SamsungOneLatinWeb;
        padding-bottom: 10px;
    }
    &Product {
        border-style: none !important;
        cursor: auto !important;
    }
    &Service{
        background-color: #ffffff;
    }
    &Service:hover {
        @include lg{
            opacity: 1;
            transform: scale(1.02);               
        }
    }
}

.servicePickerDivider{
    text-align: center;
    margin: 0px 36px 35px 36px;
    @include lg {
        display: none;
    }
}

.servicePickerDivierLineLeft {
    width: 40%;
    float: left;
    transform: translateY(10px);
    opacity: 0.7;
}

.servicePickerDivierLineRight {
    width: 40%;
    float: right;
    transform: translateY(10px);
    opacity: 0.7;
}

.serviePickerDividerText {
    width: 19px;
    height: 22px;
    font-family: SamsungOneLatinWeb;
    font-size: 14px;
    font-weight: bold;
    font-style: normal;
    font-stretch: normal;
    line-height: 1.57;
    letter-spacing: normal;
    color: #6f6f6f;
}

.recommended {
    @include lg {
        color: blue;
        text-align: center;
        margin-top: 25px;
        left: 50%;
        transform: translateX(-50%);
        position: absolute;            
    }
    @include sm {
        color: blue;
        text-align: center;
        margin-top: -225px;
        left: 50%;
        transform: translateX(-50%);
        position: absolute;            
    }
}

.mailInText {
    cursor: default;
    @include lg {
        color: #222425;
        text-align: center;
        width: 100%;
        font-size: 16px;
        font-weight: bold;
        font-style: normal;
        font-stretch: normal;
        line-height: normal;
        letter-spacing: normal;
        margin-top: 12px;
        left: 50%;
        transform: translateX(-50%);
        position: absolute;            
    }
    @include sm {
        color: #222425;
        text-align: center;
        width: 100%;
        font-size: 14px;
        font-weight: bold;
        font-style: normal;
        font-stretch: normal;
        line-height: normal;
        letter-spacing: normal;
        margin-top: -235px;
        left: 50%;
        transform: translateX(-50%);
        position: absolute;            
    }
}

.recDisabled{
    color: black;
    opacity: 0.5;
}
.serviceDisabled {
    background-color: #e0e0e0;
    opacity: 0.5;
    cursor: default;
    transform: none;
    &:hover {
        opacity: 0.5;
        transform: none;
    }
}

.show-enter {
  -webkit-transform: scale(0.85);
  -ms-transform: scale(0.85);
  -o-transform: scale(0.85);
  transform: scale(0.85);
  opacity: 0;
  max-height: 0px;
}

.show-leave {
  display:none;
}

.show-enter.show-enter-active {
  -webkit-transform: scale(1);
  -ms-transform: scale(1);
  -o-transform: scale(1);
  transform: scale(1);
  opacity: 1;
  max-height: none;
  transition: all 0.5s;
}

.loaderContainer {
    position: absolute;
    top: -10px;
    left: -10px;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    width: 100%;
    cursor: default;
    & .loader {
        background: rgba(255, 255, 255, 0.9);
        height: 197px;
        position: relative;
        top: 110px;
        left: 25px;
        width: 90%;
        z-index: 99;
        cursor: default;
    }
    & .blob {
        width: 2rem;
        height: 2rem;
        background: rgba(25,25,25,0.85);
        border-radius: 50%;
        position: absolute;
        left: calc(50% - 1rem);
        top: calc(50% - 1rem);
        box-shadow: 0 0 1rem rgba(0, 0, 0, 0.25);
    }

    & .blob2 { animation: animate-to-2 1.5s infinite; }
    & .blob3 { animation: animate-to-3 1.5s infinite; }
    & .blob1 { animation: animate-to-1 1.5s infinite; }
    & .blob4 { animation: animate-to-4 1.5s infinite; }
    & .blob0 { animation: animate-to-0 1.5s infinite; }
    & .blob5 { animation: animate-to-5 1.5s infinite; }

    @keyframes animate-to-2 {
        25%, 75% { transform: translateX(-1.5rem) scale(0.75); }
        95% { transform: translateX(0rem) scale(1); }
    }

    @keyframes animate-to-3 {
        25%, 75% { transform: translateX(1.5rem) scale(0.75); }
        95% { transform: translateX(0rem) scale(1); }
    }

    @keyframes animate-to-1 {
        25% { transform: translateX(-1.5rem) scale(0.75); }
        50%, 75% { transform: translateX(-4.5rem) scale(0.6); }
        95% { transform: translateX(0rem) scale(1); }
    }

    @keyframes animate-to-4 {
        25% { transform: translateX(1.5rem) scale(0.75); }
        50%, 75% { transform: translateX(4.5rem) scale(0.6); }
        95% { transform: translateX(0rem) scale(1); }
    }

    @keyframes animate-to-0 {
        25% { transform: translateX(-1.5rem) scale(0.75); }
        50% { transform: translateX(-4.5rem) scale(0.6); }
        75% { transform: translateX(-7.5rem) scale(0.5); }
        95% { transform: translateX(0rem) scale(1); }
    }

    @keyframes animate-to-5 {
        25% { transform: translateX(1.5rem) scale(0.75); }
        50% { transform: translateX(4.5rem) scale(0.6); }
        75% { transform: translateX(7.5rem) scale(0.5); }
        95% { transform: translateX(0rem) scale(1); }
    }


    & .spinner {
        position: absolute;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 70px;
        text-align: center;
        top: 50%;
    }

    & .loaderWarning {
        position: absolute;
        color: #000000 !important;
        font-weight: 800;
        font-size: 18px;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 100%;
        text-align: center;
        top: 50%;
    }   

    @keyframes bouncedelay {
      0%, 80%, 100% {
        transform: scale(0);
      }
      40% {
        transform: scale(1);
      }
    }

    & .bounce {
      width: 18px;
      height: 18px;
      background-color: #000;
      -webkit-border-radius: 100%;
      border-radius: 100%;
      display: inline-block;
      transform: scale(0);
      animation: bouncedelay 1.4s infinite ease-in-out;
      animation-fill-mode: both;
    }

    & .bounceOne {
      animation-delay: -0.32s;
    }

    & .bounceTwo {
      animation-delay: -0.16s;
    }

    & .bounceThree {

    }    
}
```

}

@media screen and \(max-width: 1024px\){ .modelPickerList{ display: none !important; } }

