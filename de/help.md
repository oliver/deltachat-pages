---
title: Hilfe
layout: default-de
---



<!-- GENERATED FILE -- DO NOT EDIT -->



# Hilfe

- [Allgemein](#general)
- [Gruppen](#groups)
- [Verschlüsselung](#encryption)
- [Multi-client](#multiclient)
- [Verschiedenes](#miscellaneous)

# Allgemein

## An wen kann ich schreiben?

- Mit Delta Chat können Sie an Benutzer, die Delta Chat verwenden, schreiben - und an Benutzer, die irgend einen anderen E-Mail-Client verwenden! Dies ist einer der größten Unterschiede zu anderen Messengern: Ihre Kontakte müssen _nicht_ denselben Messenger wie Sie verwenden.

## Welche Vorteile hat Delta Chat gegenüber anderen Messengern?

- _Independent_ of any company or services. _You_ own your data.
- Ihre Daten landen nicht auf zentralen Servern. So schützt Delta Chat im Gegensatz zu den meisten anderen Messengern sogar die Metadaten, d.h. wer mit wem kommuniziert
- Sie geben die Inhalte Ihres Adressbuches nicht weiter - was auch illegal ist, wenn Sie sich nicht die Zustimmung aller Ihrer Freunde, Bekannten und Geschäftspartner eingeholt haben.
- _Fast_ by the use of Push-IMAP
- _Riesige Nutzerbasis_ - Sie können auch Leute erreichen, die Delta Chat _nicht_ verwenden!
- _Kompatibel_, überprüfbar, Open Source
- _Elegant_ and _simple_ user interface
- _Distributed_ system
- _No Spam_ - only messages of known users are shown by default
- _Reliable_ - safe for professional use
- _Trustworthy_ - can even be used for business messages
- fully _Open Source_ and _Standards_ based

## Was, wenn der Empfänger kein Delta Chat verwendet?

- Der Empfänger erhält dann eine normale E-Mail, auf die er auch antworten kann. Seine Antwort erscheint dann wie gewohnt im Delta Chat Messenger

## Welche Nachrichten erscheinen in Delta Chat?

In Delta Chat erscheinen automatisch nur:

- Nachrichten von Kontakten aus Ihrem **Adressbuch**
- Nachrichten von Kontakten, die Sie **selbst kontaktiert** haben
- **Antworten** auf Ihre Nachrichten

Alle anderen Nachrichten werden _nicht_ automatisch angezeigt. Über den Menüpunkt **Kontaktanfragen** können Sie sich aber eine Übersicht der weiteren Nachrichten anzeigen lassen und gegebenenfalls einen Chat starten.

## Was ist mit Spam?

- Da Nachrichten von komplett unbekannten Absendern nicht direkt angezeigt werden, werden Sie in Delta Chat der Regel **keinen Spam** sehen.
- As messages from unknown contacts do not pop up automatically, normally, there's **no spam**.
- Bei Bedarf können Sie unerwünschte Kontakte aber jederzeit **blockieren**.

## Unterstützt Delta Chat Bilder, Videos und Dateianhänge?

- Ja.

## Unterstützt Delta Chat HTML-E-Mails?

- Ja.

# Gruppen

## Wie kann ich eine neue Gruppe erstellen?

- Select **Add group** from the "Sandwich menu" in the upper left corner of the chat overview.
- Wählen Sie dann alle **Gruppenmitglieder** aus und klicken auf den Haken oben rechts; auf der nächsten Seite können Sie noch einen **Gruppennamen** vergeben.
- Sobald Sie eine **erste Nachricht** in der Gruppe schreiben, werden alle Gruppenmitglieder über die neue Gruppe informiert und können auch dort schreiben (solange Sie in der neuen Gruppe keine Nachricht geschrieben haben, ist sie für die anderen Mitglieder noch nicht sichtbar).

## Wer kann Mitglieder hinzufügen oder löschen?

- Jedes Gruppenmitglied hat **dieselben Rechte** wie jedes andere. Jeder kann daher jeden löschen oder weitere Mitglieder hinzufügen.
- Um die Mitglieder zu verwalten einfach in der Gruppe auf den Gruppennamen klicken.

## Ich habe mich selbst versehentlich gelöscht.

- Da Sie selbst nun kein Gruppenmitglied mehr sind, können Sie sich auch nicht selbst wieder hinzufügen. Bitten Sie ein anderes Gruppenmitglied in einem normalen Chat, Sie wieder hinzuzufügen.

## Ich möchte keine Nachrichten einer Gruppe mehr empfangen.

- **Löschen** Sie entweder sich selbst als Gruppenmitglied oder den Chat selbst. Möchten Sie später wieder an der Gruppe teilnehmen, müssen Sie von einem noch aktiven Mitglied hinzugefügt werden.
- Alternativ können Sie eine Gruppe auch nur **stummschalten** - Sie erhalten dann alle Nachrichten und können bei Bedarf auch noch schreiben; es erfolgt dann aber keine Benachrichtigung mehr bei neuen Nachrichten.

# Verschlüsselung {#encryption}

## Gibt es eine Ende-zu-Ende-Verschlüsselung?

- Ja.

## Was muss ich tun, um die Ende-zu-Ende-Verschlüsselung zu aktivieren?

- Nichts.

- Delta Chat (und andere [Autocrypt](https://autocrypt.org)-kompatible E-Mail-Programme) tauschen die Schlüssel selbständig mit den ersten versendeten Nachrichten aus.
Danach ist die Verbindung Ende-zu-Ende-verschlüsselt. Verwenden Sie oder Ihr Chatpartner zwischenzeitlich ein Programm, das nicht automatisch Ende-zu-Ende verschlüsseln kann, wird die Ende-zu-Ende-Verschlüsselung automatisch ausgesetzt - und automatisch wieder begonnen, sobald die verwendeten Programme dies unterstützten.

- Wenn Sie die Ende-zu-Ende-Verschlüsselung _deaktivieren_ möchten, können Sie dies in unter _Fortgeschrittene Einstellungen_ tun.
Wie gesagt, standardmäßig ist sie _an_ und die Verbindung sicher, sobald dies möglich ist.

## Wird ohne Ende-zu-Ende-Verschlüsselung gar nicht verschlüsselt?

- Doch, es findet i.d.R. eine sog. Transportverschlüsselung statt; allerdings ist diese nicht ununterbrochen und so sind die Nachrichten unverschlüsselt auf Ihrem Server
und dem Server der Anbieter. Dies ist der Standard der bisherigen E-Mail-Kommunikation und bei vielen anderen Messengern.


## Wie kann ich die Verschlüsselung überprüfen?

- Wird neben der Nachricht wird ein **kleines Schloss** angezeigt, sagt dieses aus, dass die Nachricht ende-zu-ende-verschlüsselt ist _und_ wirklich vom angegebenen Absender kommt _und_ dass Ihre Antwort ebenfalls ende-zu-ende-verschlüsselt wird.
- Wird dort **kein Schloss** angezeigt, ist die Nachricht i.d.R. Transportverschlüsselt, z.B. weil Sie oder der Absender die Ende-zu-Ende-Veschlüsselung deaktiviert haben oder ein Programm verwenden, das diese nicht unterstützt.


## Wie kann ich den Absender überprüfen?

Den angegebenen Absender können Sie im Profil des Chatpartners unter der die Option "Verschlüsselung" überprüfen:

- bei einer Ende-zu-Ende-Verschlüsselung werden hier zwei Zahlen-Buchstaben-Folgen (sog. Fingerabdrücke) angezeigt; vergleichen Sie diese mit der Anzeige auf dem Gerät des Partners über einen anderen Kanal (persönliches Treffen, Telefon, ...)
- bei einer Transportverschlüsselung wird dieser Status hier angezeigt.


## Welches Verfahren wird für die Ende-zu-Ende-Verschlüsselung verwendet?

- OpenPGP. Der Schlüsselaustausch findet automatisch über den [Autocrypt](https://autocrypt.org)-Standard statt.

## Kann ich meinen bestehenden privaten Schlüssel weiterverwenden?

- Ja. The best way is to send an Autocrypt Setup Message from the other e-mail client. Look for sth. like **Start Autocrypt Setup Transfer** in the settings of the other client and follow the instructions shown there.

- Alternativ können Schlüssel unter "Erweiterte Einstellungen / Schlüssel verwalten" importiert werden. Achtung: Der private Schlüssel darf nicht mit einem Passwort geschützt sein, bzw. dieses muss bei Bedarf zuvor entfernt werden.

Wenn Sie keine Schlüssel haben, generiert Delta Chat automatisch einen für Sie; Sie müssen sich darum nicht kümmern.

# Mehrere Geräte verwenden {#multiclient}

## Kann ich Delta Chat auf mehreren Geräten gleichzeitig verwenden?

- Ja. Wenn Sie auf **dasselbe Konto** von verschiedenen Geräten zugreifen möchten (Multi-Client), müssen Sie den für die Verschlüsselung notwendigen **privaten Schlüssel übertragen:**

 - Wählen Sie auf dem ersten Gerät "Fortgeschrittene Einstellungen / Private Schlüssel verwalten / Exportieren nach Downloads"
 - Kopieren Sie den Schlüssel lokal via USB von Download-Verzeichnis des ersten Geräts in das Download-Verzeichnis des Zielgeräts. 
 - Auf dem Zielgerät wählen Sie dann "Fortgeschrittene Einstellungen / Private Schlüssel verwalten / Importieren aus Downloads"

- Für die Standardanwendung von Delta Chat - _ein_ Endgerät pro Konto, ähnlich wie bei den meisten anderen Messengern - ist all dies nicht notwendig.

- _Eingehende_ Nachrichten werden dabei auf allen Geräten sofort angezeigt, _ausgehende_ Nachrichten werden über Gerätegrenzen hinweg aktuell alle ca. 30 Minuten synchronisiert. Wenn wir genügend [Unterstützung](contribute) bekommen, ist geplant, dies noch weiter zu verbessern.


# Verschiedenes

## Does Delta Chat work with _my_ e-mail-provider?

- With a rather good chance: Yes :)  
  However, some providers need special options to work properly; users have collected some of them in the forum at [Provider Overview](https://support.delta.chat/t/provider-overview/)


## Ich bin an technischen Details interessiert. Gibt es hierzu weitere Infos?

- Ja, auf der Seite [Standards used in Delta Chat]({% include standards-url %}).
