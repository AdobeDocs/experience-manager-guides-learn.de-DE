---
title: Konfiguration des AEM Guides Editors
description: Konfigurieren des Editors für AEM Guides
exl-id: 437d9598-4afc-431f-81bd-6762e22656b7
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '780'
ht-degree: 0%

---

# Konfiguration des XML-Editors

Wenn Sie in einer restriktiven Umgebung arbeiten, können Sie festlegen, welche Funktionen Ihre Autoren sehen können, indem Sie die Editor-Konfiguration in einem bestimmten Ordnerprofil anpassen. Durch die Anwendung dieses Ordnerprofils kann sich das Erscheinungsbild des Editors selbst, die CSS-Vorlagen, die verfügbaren Snippets und die Beschriftungen der Inhaltsversion ändern.

Beispieldateien, die Sie für diese Lektion verwenden können, finden Sie in der Datei [xmleditorconfiguration.zip](assets/xmleditorconfiguration.zip) .

>[!VIDEO](https://video.tv.adobe.com/v/342762?quality=12&learn=on)

## Anpassen der standardmäßigen Konfiguration der Editor-Benutzeroberfläche

Sie können die standardmäßige Benutzeroberflächenkonfiguration immer auf Ihr lokales System herunterladen, Änderungen daran im Texteditor Ihrer Wahl vornehmen und sie erneut hochladen.

1. Klicken Sie im Navigationsbildschirm auf das Symbol [!UICONTROL **Tools**] .

   ![Werkzeugsymbol](images/reuse/tools-icon.png)

1. Wählen Sie im linken Bereich **Führungslinien** aus.

1. Klicken Sie auf die Kachel [!UICONTROL **Ordnerprofile**] .

   ![Ordnerprofile](images/reuse/folder-profiles-tile.png)

1. Wählen Sie ein Ordnerprofil aus.

1. Klicken Sie auf die Registerkarte [!UICONTROL **XML-Editor-Konfiguration**] .

1. Klicken Sie auf [!UICONTROL **Download**] Standard.

   ![Download-Standard](images/lesson-4/download-default.png)

Sie können den Inhalt jetzt in einem Texteditor öffnen und ändern. Das Handbuch zur Installation und Konfiguration von AEM Guides _enthält Beispiele zum Entfernen, Anpassen oder Hinzufügen von Funktionen zur Benutzeroberflächenkonfiguration._

## Hochladen der geänderten Konfiguration der XML-Editor-Benutzeroberfläche

Nach der Anpassung der Benutzeroberflächenkonfiguration können Sie sie hochladen. Beachten Sie, dass eine Beispielkonfigurationsdatei _ui-config-restricted-editor.json_ mit den unterstützenden Themen für diese Lektion bereitgestellt wird.

1. Klicken Sie im Ordnerprofil auf die Registerkarte [!UICONTROL **XML-Editor-Konfiguration**] .

1. Klicken Sie unter &quot;Konfiguration der XML-Editor-Benutzeroberfläche&quot;auf [!UICONTROL **Hochladen**].

   ![Hochladen](images/lesson-4/upload.png)

1. Doppelklicken Sie auf die Datei für Ihre geänderte Benutzeroberflächenkonfiguration oder wie hier gezeigt, auf die bereitgestellte Beispieldatei.

   ![Beispielkonfigurationsdatei](images/lesson-4/sample-config-file.png)

1. Klicken Sie oben links im Bildschirm auf [!UICONTROL **Speichern**] .

Sie haben die geänderte Benutzeroberflächenkonfiguration erfolgreich hochgeladen.

## Anpassen des Layouts der CSS-Vorlage

Wie bei der Benutzeroberflächenkonfiguration können Sie auch das CSS-Vorlagenlayout herunterladen. Sie können sie in einem Texteditor öffnen und vor dem Hochladen Änderungen vornehmen, um das Erscheinungsbild Ihres Themas anzupassen.

1. Klicken Sie im Navigationsbildschirm auf das Symbol [!UICONTROL **Tools**] .

   ![Werkzeugsymbol](images/reuse/tools-icon.png)

1. Wählen Sie im linken Bereich **Führungslinien** aus.

1. Klicken Sie auf die Kachel [!UICONTROL **Ordnerprofile**] .

   ![Ordnerprofile](images/reuse/folder-profiles-tile.png)

1. Wählen Sie ein Ordnerprofil aus.

1. Klicken Sie auf die Registerkarte [!UICONTROL **XML-Editor-Konfiguration**] .

1. Klicken Sie unter &quot;CSS-Vorlagenlayout&quot;auf [!UICONTROL **Download**].

   ![CSS herunterladen](images/lesson-4/download-css.png)

Jetzt können Sie den CSS-Inhalt in einem Texteditor ändern und speichern.

## Laden Sie das geänderte CSS-Vorlagenlayout hoch

Nach dem Anpassen des Layouts der CSS-Vorlage können Sie es hochladen. Beachten Sie, dass eine Beispieldatei _css-layout-ONLY-draft-comment-change.css_ mit den unterstützenden Themen für diese Lektion bereitgestellt wird. Diese Datei enthält nur die Entwurfskommentänderung, während _css-layout-draft-comment-change.css_ die gesamte Datei ist, die Ihnen nur zu Test- oder Prüfungszwecken zur Verfügung steht.

1. Klicken Sie im Ordnerprofil auf die Registerkarte [!UICONTROL **XML-Editor-Konfiguration**] .

1. Klicken Sie unter &quot;Layout der CSS-Vorlage&quot;auf [!UICONTROL **Hochladen**].

   ![CSS hochladen](images/lesson-4/upload-css.png)

1. Doppelklicken Sie auf die Datei für Ihr eigenes benutzerdefiniertes CSS-Layout oder die hier angezeigte Beispieldatei.

   ![CSS-Beispieldatei ](images/lesson-4/sample-css-file.png)

1. Klicken Sie oben links im Bildschirm auf [!UICONTROL **Speichern**] .
Sie haben das angepasste CSS-Vorlagenlayout erfolgreich hochgeladen.

## Bearbeiten von XML-Editor-Snippets

Snippets sind wiederverwendbare Inhaltselemente, die für ein Produkt oder eine Gruppe spezifisch sein können. Beachten Sie, dass Beispielsegmente mit den Support-Dateien für diese Lektion bereitgestellt werden.

1. Klicken Sie im Navigationsbildschirm auf das Symbol [!UICONTROL **Tools**] .

   ![Werkzeugsymbol](images/reuse/tools-icon.png)

1. Wählen Sie im linken Bereich **Führungslinien** aus.

1. Klicken Sie auf die Kachel [!UICONTROL **Ordnerprofile**] .

   ![Ordnerprofile](images/reuse/folder-profiles-tile.png)

1. Wählen Sie ein Ordnerprofil aus.

1. Klicken Sie auf die Registerkarte [!UICONTROL **XML-Editor-Konfiguration**] .

1. Klicken Sie unter &quot;XML Editor Snippets&quot;auf **Upload**.

   ![Snippets hochladen](images/lesson-4/upload-snippets.png)

1. Wählen Sie Ihre eigenen Snippets oder verwenden Sie die bereitgestellten Beispiele.

   ![Beispielfragment](images/lesson-4/sample-snippet.png)

1. Klicken Sie oben links im Bildschirm auf [!UICONTROL **Speichern**] .

Sie haben dem Editor erfolgreich neue Snippets hinzugefügt.

## Anpassen der Beschriftungen der XML-Inhaltsversion

Autoren können standardmäßig Titel ihrer Wahl erstellen und sie mit Themendateien verknüpfen. Dies kann zu unterschiedlichen Variationen des gleichen Etiketts führen. Um inkonsistente Beschriftungen zu vermeiden, können Sie auch aus Listen mit vordefinierten Beschriftungen wählen.

1. Klicken Sie im Navigationsbildschirm auf das Symbol [!UICONTROL **Tools**] .

   ![Werkzeugsymbol](images/reuse/tools-icon.png)

1. Wählen Sie im linken Bereich **Führungslinien** aus.

1. Klicken Sie auf die Kachel [!UICONTROL **Ordnerprofile**] .

   ![Ordnerprofile](images/reuse/folder-profiles-tile.png)

1. Wählen Sie ein Ordnerprofil aus.

1. Klicken Sie auf die Registerkarte [!UICONTROL **XML-Editor-Konfiguration**] .

1. Klicken Sie unter &quot;Beschriftungen der XML-Inhaltsversion&quot;auf [!UICONTROL **Download**].

   ![Beschriftungen herunterladen](images/lesson-4/download-labels.png)

Jetzt können Sie die Beschriftungen nach Bedarf anpassen.

## Hochladen von XML-Inhaltsversionsbeschriftungen

Nachdem Sie die Beschriftungen heruntergeladen und geändert haben, können Sie das Thema &quot;XML Content Version Label&quot;hochladen. Sie können die Beispieldatei _label.json_ verwenden, die mit den unterstützenden Themen für diese Lektion bereitgestellt wird.

1. Klicken Sie im Ordnerprofil auf die Registerkarte [!UICONTROL **XML-Editor-Konfiguration**] .

1. Klicken Sie unter &quot;Beschriftungen der XML-Inhaltsversion&quot;auf &quot;[!UICONTROL **Upload**]&quot;.

   ![Beschriftungen hochladen](images/lesson-4/upload-labels.png)

1. Doppelklicken Sie auf die Datei für Ihre eigenen benutzerdefinierten Beschriftungen oder die hier angezeigte Beispieldatei.

   ![Beispielbeschriftungsdatei](images/lesson-4/sample-labels-file.png)

1. Klicken Sie oben links im Bildschirm auf [!UICONTROL **Speichern**] .

Sie haben erfolgreich benutzerdefinierte XML-Inhaltsversionsbeschriftungen hochgeladen.
