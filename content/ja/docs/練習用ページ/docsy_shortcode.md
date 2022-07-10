---
categories: ["IT技術"]
tags: ["hugo", "markdown", "Docsy"]
title: "Docsy_shortcode"
linkTitle: "Docsy Shortcode"
date: 2022-07-10
description: Docsy shortcode 練習
---

{{% alert title="Primary" color="primary" %}}
This is a warning.
{{% /alert %}}


{{% alert title="Info" color="info" %}}
This is a warning.
{{% /alert %}}


{{% alert title="Warning" color="warning" %}}
This is a warning.
{{% /alert %}}

{{< tabpane code=false >}}
  {{% tab header="**Languages**:" disabled=true /%}}
  {{% tab header="English" lang="en" %}}
  ![Flag United Kingdom](flags/uk.png)
    Englishほげほげ
  {{% /tab %}}

  {{< tab header="German" lang="de" >}}
    Germanほげほげ
  {{< /tab >}}


  {{< tab header="Japanese" lang="ja" >}}
    Japaneseほげほげ
  {{< /tab >}}



  {{% tab header="Swahili" lang="sw" %}}
　　　Swahiliほげほげ
  {{% /tab %}}


{{% /tabpane %}}


{{< card-code header="**C**" lang="C" >}}
#include <stdio.h>
#include <stdlib.h>

int main(void)
{
  puts("Hello World!");
  return EXIT_SUCCESS;
}
{{< /card-code >}}

{{< cardpane >}}
  {{< card header="Header card 1" >}}
    Content card 1
  {{< /card >}}
  {{< card header="Header card 2" >}}
    Content card 2
  {{< /card >}}
  {{< card header="Header card 3" >}}
    Content card 3
  {{< /card >}}
{{< /cardpane >}}