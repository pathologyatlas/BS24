







```
r language BS24, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis sevalemer, kayekselat, kronik böbrek yetmezliği, gastrointestinal sistem etkisi TR, echo = (language == "TR")
## BS24 - sevalemer, kayekselat, kronik böbrek yetmezliği, gastrointestinal sistem etkisi {#sec-BS24 }
```


```
asis Kayexalate, Sevelamer, Gastrointestinal tract injury, chronic kidney failure EN, echo = (language == "EN")
## BS24 - Kayexalate, Sevelamer, Gastrointestinal tract injury, chronic kidney failure {#sec-BS24 }
```






```
r BS24 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS24-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS24/HE.html",
  file = "./screenshots/BS24-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS24/HE.html](https://images.patolojiatlasi.com/BS24/HE.html)





```
asis, echo = (language == "TR")

**sevalemer, kayekselat, kronik böbrek yetmezliği, gastrointestinal sistem etkisi**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS24-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS24/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS24/HE.html)
```

```
asis, echo = (language == "EN")

**Kayexalate, Sevelamer, Gastrointestinal tract injury, chronic kidney failure**

[![Click for Full Screen WSI](./screenshots/BS24-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS24/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS24/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS24/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS24/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

sevalemer, kayekselat, kronik böbrek yetmezliği, gastrointestinal sistem etkisi

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

Kayexalate, Sevelamer, Gastrointestinal tract injury, chronic kidney failure

:::

```









:::::










