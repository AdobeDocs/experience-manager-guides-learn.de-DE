---
title: Schlüssel
description: Mit Schlüsseln können Sie beim Arbeiten mit DITA in AEM Guides Variableninformationen in einfügen
exl-id: cb64e094-fe6d-4a5e-8f0e-25ae58aaa2c6
TQID: https://experienceleague.adobe.com/Uw-JiHQLITcmUtAuV-SogA6mM73A6EeCi27gUQC-8Eo
product_v2: id: fae5e35a-80c9-4b94-9352-1a060a6aab1did: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
topic_v2: id: f5c2a4bb-71ca-4d7e-8efd-442250e6ba48
source-git-commit: 27ffc636d63300fb2e99903d92cab12f0cfcbb25
workflow-type: tm+mt
source-wordcount: 546
ht-degree: 1%

---

# Schlüssel

Verschiedene Materialsätze können ähnliche Informationen enthalten, die an ausgewählten Orten angepasst werden müssen. Mit Schlüsseln können Sie bei der Arbeit mit DITA Variableninformationen in einfügen.

Beispieldateien, die Sie in dieser Lektion verwenden können, finden Sie in der Datei [keys.zip](assets/keys.zip).

>[!VIDEO](https://video.tv.adobe.com/v/342756?quality=12&learn=on)

## Schlüssel aktivieren

1. Laden Sie den Satz der bereitgestellten Beispieldateien hoch.

   a. Laden Sie die ZIP-Datei.

   B. Aktualisieren Sie die AEM-Umgebung.

   C. Wählen Sie die zu extrahierende Datei aus.

   ![Zip auswählen](images/lesson-9/select-zip.png)

   d. Klicken Sie [!UICONTROL **der oberen Symbolleiste auf**] Archiv extrahieren“.

   ![Symbolleiste](images/lesson-9/extract-archive.png)

   E. Wählen Sie im Dialogfeld den spezifischen Speicherort für zu extrahierende Dateien aus, z. B. den Ordner „Keys“.

   F. Klicken Sie auf [!UICONTROL **Weiter**].

   g. Konflikte überspringen , da sie für Inhalte, die noch nie hochgeladen wurden, nicht vorhanden sein werden.

   Std. Wählen [!UICONTROL **oben**] auf dem Bildschirm „Extrahieren“ aus.

1. Wenn die Extraktion abgeschlossen ist, klicken Sie auf [!UICONTROL **Zum Zielordner wechseln**].

   ![Bestätigung](images/lesson-9/go-to-target.png)

## Schlüssel zu referenzierten Werten auflösen

Um Schlüssel korrekt zu verwenden, müssen Benutzereinstellungen auf eine bestimmte Zuordnung als Stammzuordnung verweisen. Innerhalb dieser Zuordnung befindet sich eine Sammlung von Schlüsseln, die innerhalb einer Themengruppe gruppiert sind. Durch Öffnen der Zuordnung und der Themen werden die Schlüssel zu den Werten aufgelöst, auf die diese Zuordnung verweist.

1. Geben Sie eine Stammzuordnung an.

   a. Öffnen Sie auf dem Bildschirm Schlüssel eine Karte.

   B. Konfigurieren Sie die Benutzereinstellungen.

   C. Klicken Sie auf [!UICONTROL **Symbol**] Benutzereinstellungen“ in der oberen Symbolleiste.

   ![Symbolleiste oben](images/lesson-9/author-view.png)

   d. Klicken Sie auf das Schlüsselsymbol, um eine **Stammzuordnung** anzugeben, die zum Auflösen von Schlüsseln verwendet wird.

   E. Aktivieren Sie die Kontrollkästchen für jede gewünschte Assets.

   ![Assets-Dropdown](images/lesson-9/select-assets.png)

   F. Klicken Sie auf [!UICONTROL **Auswählen**].

   g. **Speichern** der Benutzereinstellungen.

1. Navigieren Sie zur **Kartenansicht**.

1. Öffnet die angegebene Zuordnung.

Die Schlüssel werden aufgelöst.

## Manuelles Hinzufügen eines neuen Keydef

1. Öffnen Sie eine Zuordnung mit einer angegebenen Stammzuordnung.

1. Schlüssel auswählen.

   ![Dropdown-Liste Schlüssel](images/lesson-9/hybrid-key.png)

1. Fügen Sie eine neue Keydef ein.

   a. Klicken Sie auf eine gültige Position in der Karte.

   B. Wählen Sie das Symbol **Keydef** in der oberen Symbolleiste aus.

   ![Keydef-Symbolleiste](images/lesson-9/key-icon.png)

   C. Geben Sie im Dialogfeld Keydef einfügen einen eindeutigen Wert für Schlüssel ein, der für die erstellte Definition sinnvoll ist.

   d. Klicken Sie [!UICONTROL **Einfügen**].

1. Hinzufügen von Themen innerhalb der Keydef.

   a. Klicken Sie auf das [!UICONTROL **Element einfügen**]-Symbol in der oberen Symbolleiste.

   ![Keydef-Symbolleiste](images/lesson-9/add-icon.png)

   B. Suchen Sie im Dialogfeld Element einfügen nach „topicMeta“ und wählen Sie es aus.

1. Fügen Sie Schlüsselwörter innerhalb des Themas hinzu.

   a. Klicken Sie auf das [!UICONTROL **Element einfügen**]-Symbol in der oberen Symbolleiste.

   ![Keydef-Symbolleiste](images/lesson-9/add-icon.png)

   B. Suchen Sie im Dialogfeld Element einfügen nach „Keywords“ und wählen Sie diese aus.

1. Fügen Sie ein Keyword innerhalb des TopicMeta hinzu.

   a. Klicken Sie auf das [!UICONTROL **Element einfügen**]-Symbol in der oberen Symbolleiste.

   ![Keydef-Symbolleiste](images/lesson-9/add-icon.png)

   B. Suchen Sie im **Element einfügen** und wählen Sie „Keyword“ aus

1. Geben Sie den Wert für die keydef in das Keyword ein.

In der Karte sollte Ihr Keydef nun in etwa wie folgt aussehen:

![Keydef beendet](images/lesson-9/keydef.png)

## Konfigurieren einer Keydef als Snippet

Snippets sind kleine Inhaltsfragmente, die in verschiedenen Themen in Ihrem Dokumentationsprojekt wiederverwendet werden können. Anstatt jede Keydef manuell zu generieren, können Sie eine einzelne Keydef als Snippet konfigurieren.

1. Ein Keydef-Element in der Zuordnung auswählen.

1. Klicken Sie im Kontextmenü auf [!UICONTROL **Ausschnitt erstellen**].

1. Fügen Sie im Dialogfeld Neues Snippet einen Titel und eine Beschreibung hinzu.
Möglicherweise möchten Sie auch vorhandene Schlüssel oder Schlüsselwortdefinitionen aus dem Inhalt entfernen.

1. Klicken Sie auf [!UICONTROL **Erstellen**].

1. Wählen Sie im linken Bedienfeld die Option **Snippets** aus.

1. Ziehen Sie das soeben erstellte Snippet per Drag-and-Drop aus dem Snippets-Bedienfeld auf die Karte.

1. Aktualisieren Sie die Keydef nach Bedarf mithilfe der Inhaltseigenschaften.
Nach dem Speichern und Aktualisieren ist dieser Schlüsselsatz für alle Benutzenden verfügbar, die eine Zuordnung definiert haben, die dieselbe Stammzuordnung enthält.
