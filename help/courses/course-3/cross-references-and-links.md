---
title: Querverweise und Links
description: Erstellen von Querverweisen und Links in AEM Guides
exl-id: bee7d50f-cbdd-4ac8-b15b-101febc4ae80
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '348'
ht-degree: 0%

---

# Querverweise und Links

Der XML-Editor und DITA bieten eine leistungsstarke Möglichkeit, Themen miteinander zu verknüpfen. Es ist wichtig, Ihre Inhaltsverweise effektiv zu verwalten. Dazu gehört auch die Arbeit mit eindeutigen ID-Werten.

Beispieldateien, die Sie für diese Lektion verwenden können, finden Sie in der Datei .
[crossreferencesandlinks.zip](assets/crossreferencesandlinks.zip)

>[!VIDEO](https://video.tv.adobe.com/v/342764?quality=12&learn=on)

## Erstellen eines Querverweises auf ein externes Thema

Es ist möglich, einen externen Querverweis zu erstellen, indem Sie ein Thema aus dem Repository in eine geöffnete Datei ziehen und dort ablegen. Um jedoch fehlerhafte Querverweise zu vermeiden, muss zunächst eine ID für einen Wert definiert werden, der mit dem übergeordneten Element verknüpft ist. Dies ist eine einfache Möglichkeit, einen Querverweis zu erstellen und dabei sicherzustellen, dass IDs korrekt zugewiesen sind.

1. Öffnen Sie eine Datei, in die Sie einen externen Querverweis einfügen möchten.

1. Weisen Sie dem Element, auf das verwiesen werden soll, eine ID zu.

   a. Klicken Sie in das Element.

   b. Wählen Sie im Bereich &quot;Inhaltseigenschaften&quot;die Option **ID** aus der Dropdown-Liste &quot;Attribut&quot;.

   c. Geben Sie einen logischen Namen in das Feld Wert ein.

   d. Zeigen Sie das Element und dessen Wert nach Bedarf in der **Gliederung anzeigen** an.

1. **Speichern** Sie das Thema, um sicherzustellen, dass das Repository über die aktualisierte ID verfügt.

1. Klicken Sie in der oberen Symbolleiste auf das Symbol [!UICONTROL **Verweis**] .

   ![Symbolleiste](images/lesson-7/references-icon.png)

1. Wählen Sie auf der Registerkarte **Inhaltsreferenz** die ID und die Elementpaarung aus, die Sie als Querverweis einfügen möchten.

1. Klicken Sie auf [!UICONTROL **Select**].

Der Querverweis wurde zum Thema hinzugefügt.

## Link zu einer Website

Sie können einen Link zu einer Website innerhalb eines beliebigen Themas einfügen. Weitere Informationen finden Sie im Video AEM Guides-Kurs 1 unter Verknüpfen mit Websites .


## Beschädigte Links anzeigen

Einige Änderungen können zu fehlerhaften Querverweisen führen. Dazu gehören das Löschen eines Themas, das Neuorganisieren eines Abschnitts, der einen Querverweis enthält, oder das Ändern einer ID nach dem Einfügen des Querverweises. Beachten Sie, dass ein Beispielthema _crossreferencesandlinks.zip_ mit dieser Lektion bereitgestellt wird, die dazu führt, dass mehrere der Aufzählungskreuzverweise auf internen Inhalt beschädigt werden.

1. Navigieren Sie im linken Bereich zur **Gliederung-Ansicht** .

1. Klicken Sie auf das Symbol [!UICONTROL **Filter**] .

1. Wählen Sie **Beschädigte Links** aus.

   ![Filter Dropdown](images/lesson-7/broken-links.png)

Beschädigte Links werden als anklickbare Objekte angezeigt. Sie können sie in rotem Text im Thema identifizieren.
