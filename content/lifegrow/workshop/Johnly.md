---
title: "Johnly"
menu: "workshop"
weight: -99
draft: true
img: "https://images7.alphacoders.com/691/691161.png"
workshopDate: "2018年1月21日(星期日)"
time: "下午3至5時"
place:  "Justmove"
---
<div>
                    <img  width="100%" src="{{.Params.img}}">
                </div>
                <div style="text-align:left; color:green">
                    {{.Title}}
                </div>
                <div style="text-align:left">
                    日期： {{.Params.workshopDate}}
                </div>
                <div style="text-align:left">
                    時間： {{.Params.time}}
                </div>

                <div style="text-align:left">
                    地點： {{.Params.place}}
                </div>
                <div style="text-align:center; width:50%; margin:auto; background-color:green">
                    <a style="color:white; " href="{{.URL}}"> 詳情 </a>
                </div>