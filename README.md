# Text-typeing live https://jibon87.github.io/Text-typeing/
```
Text typeing

1.  js--link ---> jquery.min.js

2.  js--link ---> js/text-type.js

3.  css--link ---> style.css   [
                                            /* --------- 
                                        text css animation 
                                        --------- */
                                        .cd-words-wrapper {
                                            display: inline-block;
                                            position: relative;
                                            text-align: left;
                                        }
                                        .cd-words-wrapper b {
                                            display: inline-block;
                                            position: absolute;
                                            white-space: nowrap;
                                            left: 0;
                                            top: 0;
                                        }
                                        .cd-words-wrapper b.is-visible {
                                            position: relative;
                                            color: #08e44ada;
                                            font-size: 2rem;
                                        }
                                        .no-js .cd-words-wrapper b {
                                            opacity: 0;
                                        }
                                        .no-js .cd-words-wrapper b.is-visible {
                                            opacity: 1;
                                        }
                                        .cd-headline.clip span {
                                            display: inline-block;
                                            padding: 0;
                                            color: #000000;
                                            font-size: 2rem;
                                            text-transform: none;
                                            font-weight: bold;
                                        }
                                        .cd-headline.clip .cd-words-wrapper {
                                            overflow: hidden;
                                            vertical-align: middle;
                                        }
                                        .cd-headline.clip .cd-words-wrapper::after {
                                            content: "";
                                            position: absolute;
                                            top: 50%;
                                            right: 0;
                                            width: 2px;
                                            height: 80%;
                                            background-color: rgb(255, 255, 255);
                                            -webkit-transform: translateY(-50%);
                                            -ms-transform: translateY(-50%);
                                            transform: translateY(-50%);
                                        }
                                        .cd-headline.clip b {
                                            opacity: 0;
                                        }
                                        .cd-headline.clip b.is-visible {
                                            opacity: 1;
                                        }
                                        .bg {
                                            background-color: #fc6d6d;
                                        }
]

4.  html 
    {
    
        <span class="header-caption" id="page-top">
            <!-- type headline start-->
            <span class="cd-headline clip is-full-width" style="display: flex;">
                <span>I'm a </span>
                <!-- ROTATING TEXT -->
                <span class="cd-words-wrapper">
                    <b class="is-visible">Developer.</b>
                    <b class="is-hidden">Professional Coder.</b>
                    <b class="is-hidden">Seo exp.</b>
                    <b class="is-hidden">youtuber.</b>
                </span>
            </span>
            <!-- type headline end -->
        </span>

    }
    
5.  active js {

}
6.  note [ 
            
         ]
