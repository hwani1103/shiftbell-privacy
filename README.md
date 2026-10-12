# 교대시계(ShiftBell) 개인정보처리방침 / Privacy Policy

## 한국어

최종 수정: 2026년 10월 12일.

교대시계에서 만드는 데이터는 기본적으로 사용자의 기기에 저장됩니다. 아래에서는 기기에 저장되는 정보, Google 서비스를 통해 처리되는 정보와 사용자가 문의할 때 개발자에게 전달되는 정보를 안내합니다.

### 기본 - 기기 안에 저장되는 데이터

근무 스케줄, 알람 설정과 알람 기록, 메모/일정, 근무시간·OT, 수면 기록, 친구 목록 등 앱에서 만드는 데이터는 사용자의 기기 안에 저장되며 개발자에게 전송되지 않습니다. 자동 수면 추정도 화면이 켜져 있는지, 충전 중인지만 기기 안에서 확인하고 그 결과를 밖으로 보내지 않습니다.

다만 아래 '사용 통계', '일정공유', '광고' 항목에 적힌 범위의 정보는 Google 서비스로 전송됩니다.

진단 파일은 Android 10 이상에서 기기 안의 Download/ShiftBell/log 폴더에 자동 저장·갱신됩니다. 이 파일에는 기기·Android 버전, 권한과 배터리 설정 상태, 알람 예약·울림 기록, 백업 기록이 들어가며 메모·일정 내용, 근무명, 친구 이름은 들어가지 않아요. 앱이 이 파일을 자동으로 전송하지 않으며, 필요할 때 사용자가 직접 찾아 보내실 수 있어요.

설정 → 부가 기능 → 진단 로그 이메일로 보내기를 누르면 공유용 .txt 파일을 앱의 임시 폴더에 만듭니다. 전송은 사용자가 메일 앱에서 직접 완료합니다. 이메일로 보내면 로그 파일, 메일에 적은 내용과 발신자 이메일 주소가 개발자에게 전달됩니다. 교대시계는 이메일 계정 정보에 접근하거나 로그를 자동 전송하지 않습니다.

### 사용 통계(Google Firebase Analytics)

앱을 개선하기 위해 Google Firebase Analytics가 앱 실행·화면 이용 같은 이용 기록, 앱 버전, 기기 종류·OS 버전, 대략적인 지역 정보와 앱 설치별 식별자를 자동으로 수집합니다. 또 어떤 기능이 얼마나 쓰이는지 알 수 있도록 알람 끄기·다시 알림 횟수, 메모·일정·수면 기록·백업 같은 기능을 사용한 횟수만 함께 기록합니다. 웹 뷰어에서 친구 근무표를 정상적으로 연 횟수는 앱 사용과 별도로 집계하며, 공유 코드나 친구 이름은 이 이벤트에 넣지 않습니다. 근무표·메모·수면 기록·알람 시각 같은 앱 데이터의 내용은 통계에 넣지 않습니다. 수집된 통계는 Google의 개인정보처리방침에 따라 처리됩니다.

앱 안정성을 확인하기 위해 알람 예약·울림 진입·갱신 및 기기 재부팅 관측 횟수, 권한과 배터리 제한 상태의 분류, 기기 제조사 범주를 Google Firebase Analytics로 전송할 수 있습니다. 원본 진단 파일이나 알람 식별자·시각, 근무표·메모·수면 기록의 내용은 이 통계에 포함하지 않습니다. 일부 관측은 다음 앱 실행 때 전송되어 실제 발생 시점과 보고 날짜가 다를 수 있습니다.

### 일정공유 기능을 쓰는 경우(Google Firebase)

'일정공유'를 켜면 친구에게 보여줄 이름과 근무 스케줄(근무 패턴·시작일·근무별 색상·날짜별 근무 변경)이 Google Firebase 서버에 저장되고, 공유 코드나 링크를 가진 사람은 누구나 볼 수 있습니다. 이를 위해 앱이 자동으로 만드는 익명 식별자가 함께 쓰이며, 메모·OT·수면 기록·알람 설정은 전송하지 않습니다.

공유를 중지하면 기기에서는 바로 꺼지고 서버의 공유 내용을 제거하는 요청이 전송됩니다. v2 공유에서는 오래된 전송이 공유를 다시 활성화하지 못하도록 중지 상태와 최소 버전 정보를 남길 수 있습니다. 인터넷에 연결되어 있지 않으면 연결된 뒤 다시 보내며, 그 전까지는 친구가 이전 근무표를 볼 수 있습니다. 친구 기기에 이미 받아 둔 근무표나 캡처는 회수할 수 없습니다.

앱을 삭제하고 다시 설치하면 새 익명 식별자가 만들어져, 이전에 공유한 데이터를 앱에서 지울 수 없게 됩니다. 재설치 전에 공유를 중지해 주세요.

한국 공휴일 변경분을 확인하려고 Firebase의 공개 문서를 드물게 읽습니다. 이 조회에 근무표·수면 기록 등 앱 내용은 보내지 않습니다. 업데이트 가능 여부는 Google Play에서 확인합니다.

이전 버전은 Firebase의 공개 업데이트 설정을 읽을 수 있으며, 이 조회에 근무표나 메모 내용을 넣지 않습니다.

### 광고 제공(Google AdMob)

앱 화면 일부에 Google AdMob 배너 광고가 표시됩니다. 광고 제공과 성과 측정을 위해 광고 SDK가 기기 식별자, IP 주소, 앱 상호작용 및 진단 정보를 처리할 수 있습니다. 앱은 근무표·알람 시각·메모 내용을 광고 요청에 넣지 않습니다.

Google의 동의 시스템에서 요구하는 경우 광고 관련 선택을 요청합니다. 설정에 광고 개인정보 설정이 표시되면 선택을 다시 확인하거나 변경할 수 있습니다. Google의 정보 처리 방식은 Google 개인정보처리방침에서 확인할 수 있습니다.

### 앱이 요청하는 권한

• 알림: 알람 사전 안내, 알람 상태 표시, 일정 알림
• 다른 앱 위에 표시: 다른 앱 사용 중에도 알람 화면을 띄우기 위함
• 정확한 알람: 설정한 시각에 알람을 예약하기 위함

권한을 허용하지 않아도 앱은 계속 쓸 수 있지만, 위 기능 중 일부가 제한될 수 있습니다.

• 잠금화면 알람 표시: 휴대전화가 잠겼을 때 알람 화면을 표시하기 위한 전체 화면 알림 권한입니다.

### 데이터 보관 및 삭제

기기 안의 데이터는 앱을 삭제하면 함께 삭제됩니다.

단, '백업' 기능(자동 백업 포함)으로 만든 파일은 기기의 다운로드/ShiftBell 폴더에 남아 앱을 삭제해도 지워지지 않습니다. 이 파일은 암호화되지 않았고 근무표·알람 기록·메모/일정·OT·수면 기록·친구 목록 등이 들어 있으니 다른 사람에게 보내지 않도록 주의하고, 필요 없으면 파일 관리자에서 직접 삭제해 주세요. 백업 파일은 자동으로 외부에 전송되지 않지만, 클라우드 동기화 폴더 등으로 옮기면 그 서비스의 정책이 적용됩니다.

Download/ShiftBell/log의 진단 파일도 앱 삭제 후 남을 수 있습니다. 이 파일에는 기기 정보, 권한 상태, 알람·백업 기록이 들어 있으므로 필요 없으면 파일 관리자에서 직접 삭제해 주세요.

백업은 Android 10 이상에서만 지원됩니다. 앱을 삭제하고 다시 설치하면 이전 백업을 자동으로 찾지 못하므로, 첫 화면의 '기존에 쓰시던 분이라면'에서 '불러오기'를 눌러 파일을 직접 골라야 합니다.

일정공유 데이터의 삭제는 위 '일정공유' 안내를, 사용 통계·광고 데이터의 보관은 Google의 정책을 따릅니다.

공유용 진단 로그는 앱의 임시 폴더에 저장되며 앱을 삭제하면 함께 삭제됩니다. 사용자가 이메일이나 다른 앱으로 보낸 사본은 해당 서비스와 수신자가 보관합니다.

이전 버전에서 만든 데이터는 현재 화면에 해당 기능이 없어도 사용자가 삭제하거나 앱을 제거하기 전까지 기기에 남을 수 있습니다.

개발자가 이메일로 받은 문의 내용, 발신자 이메일 주소와 진단 첨부파일은 문의 대응과 문제 확인을 위해 사용하며, 문의 해결 후 30일 이내에 삭제합니다. lowvibe07@gmail.com으로 삭제를 요청하면 지체 없이 삭제합니다. 메일 서비스가 별도로 보관하는 사본에는 해당 서비스의 정책이 적용됩니다.

### 아동 대상 서비스가 아닙니다

본 앱은 만 14세 미만 아동을 대상으로 하지 않으며, 아동의 개인정보를 의도적으로 수집하지 않습니다.

### 문의처

앱 이용 중 궁금한 점이나 문의사항은 아래로 연락해 주세요.
• 티스토리: lowvibe07.tistory.com
• 카카오톡 오픈채팅: '교대시계 앱' 검색
• 개발자 이메일: lowvibe07@gmail.com

기능과 데이터 처리 범위는 설치된 버전 및 사용자가 켠 기능에 따라 달라집니다. 이 방침 갱신이 새 앱 버전의 공개 완료를 뜻하지는 않습니다.

## English

Last updated: October 12, 2026.

Your shift and alarm data is stored on your device. ShiftBell also uses Google services for usage statistics and advertising. This policy explains those services and local files.

### Data stored on your device

Your shifts, alarm settings and history, notes, work hours and overtime are stored in the app’s local database. These contents are not included in analytics events or advertising requests.

On Android 10 or later, diagnostic files are saved locally in Download/ShiftBell/log. They include device and Android versions, permission and battery settings, and alarm and backup processing records. Note contents and shift names are excluded. The app does not send these files automatically.

Settings → Additional features → Email diagnostic log creates a .txt attachment in the app’s temporary folder. You complete sending in your email app. Sending an email gives the developer the log file, the message you write and your sender email address. ShiftBell does not access your email account information or send logs automatically.

### Usage statistics (Google Firebase Analytics)

Google Firebase Analytics collects usage and device information, such as app opens, screen views, app and operating-system versions, device model, approximate region and an installation identifier. ShiftBell also records feature-use events, such as dismissing or snoozing an alarm, saving a note or creating a backup.

These events do not include shift names, alarm times, note text or other schedule contents. Statistics are processed under Google’s privacy policy.

To assess app reliability, ShiftBell may send counts of observed alarm scheduling, alarm entry, refresh and device reboot events, categories of permission and battery restrictions, and a device manufacturer category to Google Firebase Analytics. These statistics exclude original diagnostic files, alarm identifiers and times, and the contents of your schedules and notes. Some observations are sent when you next open the app, so reporting dates may differ from occurrence dates.

### App updates

App update availability is checked through Google Play.

Earlier versions may read public update settings from Firebase without including schedule or note contents in the request.

### Advertising (Google AdMob)

ShiftBell displays Google AdMob banner ads. The advertising SDK may process device identifiers, IP addresses, app interactions and diagnostics to provide and measure ads. ShiftBell does not include your shift schedule, alarm times or note contents in ad requests.

Where required by Google’s consent system, the app asks for your advertising choices. When available, use Ad Privacy Settings in Settings to review them. Google’s privacy policy describes how Google handles this information.

### Permissions the app requests

• Notifications: show alarm status and pre-alarm reminders.
• Display over other apps: show the alarm screen while you use other apps.
• Exact alarms: schedule alarms for the time you set.

You can review these permissions in Android Settings. Declining them may limit alarm notifications or prevent alarms from working as expected.

• Lock screen display: allow full-screen notifications to show the alarm screen while the phone is locked.

### Data retention and deletion

Uninstalling removes the app’s local database. Backup and diagnostic files saved in Download/ShiftBell may remain; delete them with your file manager when they are no longer needed.

Backups are not encrypted. They can contain your full local data. Keep them private. The app never uploads these files automatically. If you copy them to a cloud service or send them to someone, that service or recipient controls the copy.

The app keeps one manual backup and one automatic backup. A new file replaces the previous file of the same kind.

Google’s policies apply to retention of analytics and advertising data.

Diagnostic attachments in the app’s temporary folder are removed when the app is uninstalled. Copies you send through email or another app are retained by that service and the recipient.

Data created in earlier versions may remain on your device until you delete it or uninstall the app, even if the current interface no longer offers the feature.

The developer uses emailed support messages, sender email addresses and diagnostic attachments to respond to inquiries and investigate issues, and deletes them within 30 days after the inquiry is resolved. Deletion requests sent to lowvibe07@gmail.com are handled without undue delay. Copies retained separately by the email service are governed by that service’s policy.

### Not directed at children

This app is not directed at children under 14, and we do not knowingly collect personal information from children.

### Contact

For app support and privacy questions:
lowvibe07@gmail.com

### Korean interface and earlier versions

Some features are available only in the Korean interface. Local events, sleep records and contacts from those features can remain on the device after switching languages. Automatic sleep estimation checks screen and charging state locally.

If you enable schedule sharing in the Korean interface or used it in an earlier version, Firebase stores the display name and shared roster (pattern, start date, shift colors and date-specific changes) with an anonymous identifier. Anyone with the code or link can view it. Notes, overtime, sleep records and alarm settings are not included. Stopping sharing requests removal of shared contents; v2 may retain revocation/version metadata to prevent stale uploads from restoring them. Offline requests may be delayed, and downloaded copies cannot be recalled. Stop sharing before reinstalling: a new anonymous identity may prevent deletion of old shared data from the app. Contact lowvibe07@gmail.com for assistance.

The Korean interface reads public holiday corrections from Firebase without including schedule contents. Successful shared-calendar web views are counted separately; these events exclude share codes and contact names. Local features and data processing depend on the installed version and enabled features; this notice does not mean the new version is already available.

## Deutsch

Zuletzt aktualisiert: 12. Oktober 2026.

Deine Schicht- und Weckerdaten werden auf deinem Gerät gespeichert. ShiftBell nutzt auch Google-Dienste für Nutzungsstatistiken und Werbung. Diese Erklärung beschreibt diese Dienste und lokale Dateien.

### Auf deinem Gerät gespeicherte Daten

Deine Schichten, Weckereinstellungen und der Weckerverlauf, Notizen, Arbeitszeiten und Überstunden werden in der lokalen Datenbank der App gespeichert. Diese Inhalte werden weder in Analyseereignisse noch in Werbeanfragen aufgenommen.

Ab Android 10 werden Diagnosedateien lokal in Download/ShiftBell/log gespeichert. Sie enthalten Geräte- und Android-Versionen, Berechtigungen, Akkueinstellungen sowie Verarbeitungsprotokolle für Wecker und Sicherungen. Notizinhalte und Schichtnamen sind ausgeschlossen. Die App versendet diese Dateien nicht automatisch.

Einstellungen → Zusätzliche Funktionen → Diagnoseprotokoll per E-Mail senden erstellt einen .txt-Anhang im temporären Ordner der App. Du sendest ihn selbst in deiner E-Mail-App. Dabei erhält der Entwickler die Protokolldatei, deine Nachricht und deine Absenderadresse. ShiftBell greift nicht auf deine E-Mail-Kontoinformationen zu und versendet Protokolle nicht automatisch.

### Nutzungsstatistiken (Google Firebase Analytics)

Google Firebase Analytics erfasst Nutzungs- und Geräteinformationen, zum Beispiel App-Starts, Seitenaufrufe, App- und Betriebssystemversionen, Gerätemodell, ungefähre Region und eine Installationskennung. ShiftBell erfasst außerdem die Nutzung einzelner Funktionen, etwa das Ausschalten oder Verschieben eines Weckers, das Speichern einer Notiz oder das Erstellen einer Sicherung.

Diese Ereignisse enthalten keine Schichtnamen, Weckzeiten, Notiztexte oder sonstigen Inhalte des Schichtplans. Die Statistiken werden gemäß der Datenschutzerklärung von Google verarbeitet.

Zur Beurteilung der App-Zuverlässigkeit kann ShiftBell die Anzahl beobachteter Weckerplanungen, Weckerstarts, Aktualisierungen und Geräteneustarts sowie Kategorien von Berechtigungs- und Akkubeschränkungen und des Geräteherstellers an Google Firebase Analytics senden. Diese Statistiken enthalten keine ursprünglichen Diagnosedateien, Weckerkennungen oder Weckzeiten und keine Inhalte von Schichtplänen oder Notizen. Manche Beobachtungen werden erst beim nächsten Öffnen der App gesendet; das Berichtsdatum kann daher vom Ereignisdatum abweichen.

### App-Updates

Die Verfügbarkeit von App-Updates wird über Google Play geprüft.

Frühere Versionen können öffentliche Update-Einstellungen aus Firebase lesen, ohne Inhalte von Schichtplänen oder Notizen in der Anfrage zu übermitteln.

### Werbung (Google AdMob)

ShiftBell zeigt Bannerwerbung von Google AdMob. Das Werbe-SDK kann Gerätekennungen, IP-Adressen, App-Interaktionen und Diagnosedaten verarbeiten, um Werbung bereitzustellen und zu messen. ShiftBell nimmt deinen Schichtplan, deine Weckzeiten und Notizinhalte nicht in Werbeanfragen auf.

Wenn das Einwilligungssystem von Google es verlangt, fragt die App nach deinen Werbepräferenzen. Sofern verfügbar, kannst du diese unter Datenschutz für Werbung in den Einstellungen prüfen. Wie Google diese Informationen verarbeitet, beschreibt die Datenschutzerklärung von Google.

### Angeforderte Berechtigungen

• Benachrichtigungen: Weckerstatus und Erinnerungen vor Weckern anzeigen.
• Über anderen Apps einblenden: die Weckeransicht während der Nutzung anderer Apps anzeigen.
• Genaue Alarme: Wecker zur eingestellten Uhrzeit planen.

Du kannst diese Berechtigungen in den Android-Einstellungen prüfen. Wenn du sie ablehnst, können Weckerbenachrichtigungen eingeschränkt sein oder Wecker nicht wie erwartet funktionieren.

• Sperrbildschirm: Vollbildbenachrichtigungen erlauben, um den Wecker bei gesperrtem Telefon anzuzeigen.

### Aufbewahrung und Löschung

Beim Deinstallieren wird die lokale Datenbank der App entfernt. Sicherungen und Diagnosedateien in Download/ShiftBell können erhalten bleiben. Lösche sie mit deinem Dateimanager, wenn du sie nicht mehr brauchst.

Sicherungen sind nicht verschlüsselt. Sie können alle lokalen Daten enthalten. Bewahre sie vertraulich auf. Die App lädt diese Dateien niemals automatisch hoch. Wenn du sie in einen Cloud-Dienst kopierst oder an jemanden sendest, kontrolliert dieser Dienst oder Empfänger die Kopie.

Die App behält je eine manuelle und eine automatische Sicherung. Eine neue Datei ersetzt die vorherige Datei derselben Art.

Für Analyse- und Werbedaten gelten die Aufbewahrungsrichtlinien von Google.

Diagnoseanhänge im temporären Ordner der App werden beim Deinstallieren gelöscht. Kopien, die du per E-Mail oder mit einer anderen App sendest, werden vom jeweiligen Dienst und Empfänger aufbewahrt.

Daten aus früheren Versionen können auf dem Gerät verbleiben, bis du sie löschst oder die App deinstallierst, auch wenn die Funktion in der aktuellen Oberfläche nicht mehr angeboten wird.

Der Entwickler verwendet per E-Mail erhaltene Anfragen, Absenderadressen und Diagnoseanhänge zur Beantwortung von Anfragen und Untersuchung von Problemen und löscht sie innerhalb von 30 Tagen nach Klärung der Anfrage. Löschanfragen an lowvibe07@gmail.com werden unverzüglich bearbeitet. Für Kopien, die der E-Mail-Dienst gesondert aufbewahrt, gelten dessen Richtlinien.

### Nicht für Kinder bestimmt

Diese App richtet sich nicht an Kinder unter 14 Jahren. Wir erfassen wissentlich keine personenbezogenen Daten von Kindern.

### Kontakt

Bei Fragen zur App oder zum Datenschutz:
lowvibe07@gmail.com

### Koreanische Oberfläche und frühere Versionen

Einige Funktionen sind nur in der koreanischen Oberfläche verfügbar. Lokale Termine, Schlafdaten und Kontakte dieser Funktionen können nach einem Sprachwechsel auf dem Gerät verbleiben. Die automatische Schlafschätzung prüft Bildschirm- und Ladezustand nur lokal.

Bei aktivierter Kalenderfreigabe in dieser Oberfläche oder in einer früheren Version speichert Firebase den Anzeigenamen und freigegebenen Schichtplan (Muster, Startdatum, Schichtfarben und Änderungen einzelner Tage) mit einer anonymen Kennung. Jeder mit dem Code oder Link kann ihn sehen. Notizen, Überstunden, Schlafdaten und Weckereinstellungen sind nicht enthalten. Beim Beenden der Freigabe wird die Entfernung der freigegebenen Inhalte angefordert; v2 kann Widerrufs- und Versionsmetadaten behalten, damit alte Übertragungen die Freigabe nicht wiederherstellen. Offline-Anfragen können sich verzögern; heruntergeladene Kopien lassen sich nicht zurückholen. Beende die Freigabe vor einer Neuinstallation: Eine neue anonyme Kennung kann das Löschen alter Freigaben aus der App verhindern. Hilfe: lowvibe07@gmail.com.

Die koreanische Oberfläche liest öffentliche Feiertagskorrekturen aus Firebase ohne Schichtplaninhalte zu übermitteln. Erfolgreiche Aufrufe freigegebener Kalender im Web werden separat gezählt, ohne Freigabecodes oder Kontaktnamen in diesen Ereignissen. Funktionen und Datenverarbeitung hängen von der installierten Version und aktivierten Funktionen ab; diese Erklärung bedeutet nicht, dass die neue Version bereits verfügbar ist.

## Português (Brasil)

Última atualização: 12 de outubro de 2026.

Os dados de turnos e alarmes são armazenados no seu aparelho. O ShiftBell também usa serviços do Google para estatísticas de uso e publicidade. Esta política explica esses serviços e os arquivos locais.

### Dados armazenados no seu aparelho

Seus turnos, configurações e histórico de alarmes, notas, horários de trabalho e horas extras ficam no banco de dados local do app. Esses conteúdos não são incluídos nos eventos de análise nem nas solicitações de anúncios.

No Android 10 ou superior, arquivos de diagnóstico são salvos localmente em Download/ShiftBell/log. Eles incluem versões do aparelho e do Android, permissões, configurações de bateria e registros do processamento de alarmes e backups. Conteúdo de notas e nomes de turnos não são incluídos. O app não envia esses arquivos automaticamente.

Configurações → Recursos adicionais → Enviar log de diagnóstico por e-mail cria um anexo .txt na pasta temporária do app. Você conclui o envio no app de e-mail. Ao enviar, o desenvolvedor recebe o log, a mensagem que você escrever e seu endereço de e-mail remetente. O ShiftBell não acessa os dados da sua conta de e-mail nem envia logs automaticamente.

### Estatísticas de uso (Google Firebase Analytics)

O Google Firebase Analytics coleta informações de uso e do aparelho, como aberturas do app, telas visitadas, versões do app e do sistema, modelo do aparelho, região aproximada e um identificador de instalação. O ShiftBell também registra o uso de recursos, como desligar ou adiar um alarme, salvar uma nota ou criar um backup.

Esses eventos não incluem nomes de turnos, horários de alarmes, textos de notas nem outros conteúdos da escala. As estatísticas são processadas conforme a política de privacidade do Google.

Para avaliar a confiabilidade do app, o ShiftBell pode enviar ao Google Firebase Analytics contagens de agendamentos, inícios e atualizações de alarmes e reinicializações do aparelho observados, categorias de restrições de permissões e bateria e uma categoria do fabricante do aparelho. Essas estatísticas não incluem arquivos originais de diagnóstico, identificadores ou horários de alarmes, nem o conteúdo de escalas e notas. Algumas observações são enviadas na próxima abertura do app, por isso a data do relatório pode ser diferente da data do evento.

### Atualizações do app

A disponibilidade de atualizações do app é verificada pelo Google Play.

Versões anteriores podem consultar configurações públicas de atualização no Firebase sem incluir o conteúdo de escalas ou notas na solicitação.

### Publicidade (Google AdMob)

O ShiftBell exibe anúncios em banner do Google AdMob. O SDK de publicidade pode processar identificadores do aparelho, endereços IP, interações com o app e diagnósticos para fornecer e medir anúncios. O ShiftBell não inclui sua escala, horários de alarmes nem conteúdos de notas nas solicitações de anúncios.

Quando exigido pelo sistema de consentimento do Google, o app solicita suas preferências de publicidade. Quando disponível, use Privacidade dos anúncios nas configurações para revisá-las. A política de privacidade do Google explica como essas informações são tratadas.

### Permissões solicitadas pelo app

• Notificações: mostrar o estado dos alarmes e lembretes antes de tocarem.
• Exibir sobre outros apps: mostrar a tela de alarme durante o uso de outros apps.
• Alarmes exatos: agendar alarmes para o horário definido.

Você pode revisar essas permissões nas configurações do Android. Negá-las pode limitar as notificações ou impedir que os alarmes funcionem como esperado.

• Tela de bloqueio: permitir notificações em tela cheia para mostrar a tela do alarme com o celular bloqueado.

### Retenção e exclusão de dados

Desinstalar o app remove seu banco de dados local. Arquivos de backup e diagnóstico salvos em Download/ShiftBell podem permanecer. Exclua-os pelo gerenciador de arquivos quando não forem mais necessários.

Os backups não são criptografados. Eles podem conter todos os dados locais. Mantenha-os privados. O app nunca envia esses arquivos automaticamente. Se você os copiar para a nuvem ou enviar a alguém, o serviço ou destinatário controlará essa cópia.

O app mantém um backup manual e um automático. Um novo arquivo substitui o anterior do mesmo tipo.

As políticas do Google se aplicam à retenção dos dados de análise e publicidade.

Os anexos de diagnóstico na pasta temporária do app são removidos quando ele é desinstalado. Cópias enviadas por e-mail ou outro app ficam com o serviço e o destinatário.

Dados criados em versões anteriores podem permanecer no aparelho até você apagá-los ou desinstalar o app, mesmo que a interface atual não ofereça mais o recurso.

O desenvolvedor usa as mensagens de suporte recebidas por e-mail, os endereços dos remetentes e os anexos de diagnóstico para responder às solicitações e investigar problemas, e os exclui em até 30 dias após a resolução da solicitação. Pedidos de exclusão enviados a lowvibe07@gmail.com são atendidos sem demora indevida. Cópias mantidas separadamente pelo serviço de e-mail seguem a política desse serviço.

### Não destinado a crianças

Este app não é destinado a menores de 14 anos, e não coletamos intencionalmente informações pessoais de crianças.

### Contato

Para suporte do app ou dúvidas sobre privacidade:
lowvibe07@gmail.com

### Interface em coreano e versões anteriores

Alguns recursos estão disponíveis apenas na interface em coreano. Eventos, registros de sono e contatos locais desses recursos podem permanecer no aparelho após a troca de idioma. A estimativa automática de sono verifica o estado da tela e do carregamento apenas no aparelho.

Se você ativar o compartilhamento de escala nessa interface ou o tiver usado em uma versão anterior, o Firebase armazena o nome de exibição e a escala compartilhada (padrão, data inicial, cores dos turnos e alterações por data) com um identificador anônimo. Qualquer pessoa com o código ou link pode visualizá-la. Notas, horas extras, registros de sono e configurações de alarmes não são incluídos. Interromper o compartilhamento solicita a remoção do conteúdo; a versão v2 pode manter metadados de revogação e versão para impedir que envios antigos o restaurem. Solicitações offline podem demorar; cópias já baixadas não podem ser recolhidas. Interrompa o compartilhamento antes de reinstalar: um novo identificador anônimo pode impedir a exclusão dos dados antigos pelo app. Ajuda: lowvibe07@gmail.com.

A interface em coreano consulta correções públicas de feriados no Firebase sem incluir o conteúdo da escala. Visualizações bem-sucedidas do calendário compartilhado na web são contadas separadamente, sem códigos de compartilhamento ou nomes de contatos nesses eventos. Os recursos e o tratamento dos dados dependem da versão instalada e dos recursos ativados; esta política não significa que a nova versão já esteja disponível.

## हिन्दी

अंतिम अपडेट: 12 अक्टूबर 2026।

आपकी शिफ्ट और अलार्म का डेटा आपके डिवाइस पर सेव होता है। ShiftBell इस्तेमाल के आंकड़ों और विज्ञापनों के लिए Google की सेवाएं भी इस्तेमाल करता है। यह नीति इन सेवाओं और स्थानीय फ़ाइलों की जानकारी देती है।

### आपके डिवाइस पर सेव होने वाला डेटा

आपकी शिफ्ट, अलार्म सेटिंग और इतिहास, नोट, काम के घंटे और ओवरटाइम ऐप के स्थानीय डेटाबेस में सेव होते हैं। इनकी सामग्री इस्तेमाल के आंकड़ों या विज्ञापन अनुरोधों में शामिल नहीं की जाती।

Android 10 या नए संस्करण पर समस्या जांचने की फ़ाइलें Download/ShiftBell/log में स्थानीय रूप से सेव होती हैं। इनमें डिवाइस और Android के संस्करण, अनुमतियां, बैटरी सेटिंग तथा अलार्म और बैकअप प्रक्रिया के रिकॉर्ड होते हैं। नोट की सामग्री और शिफ्ट के नाम शामिल नहीं होते। ऐप इन फ़ाइलों को अपने आप नहीं भेजता।

सेटिंग → अतिरिक्त सुविधाएँ → जांच का लॉग ईमेल से भेजें से ऐप के अस्थायी फ़ोल्डर में .txt संलग्नक बनता है। ईमेल ऐप में आप खुद संदेश भेजते हैं। ईमेल भेजने पर डेवलपर को लॉग फ़ाइल, आपका लिखा संदेश और भेजने वाला ईमेल पता मिलता है। ShiftBell आपके ईमेल खाते की जानकारी नहीं देखता और लॉग अपने आप नहीं भेजता।

### इस्तेमाल के आंकड़े (Google Firebase Analytics)

Google Firebase Analytics ऐप खोलने, स्क्रीन देखने, ऐप और ऑपरेटिंग सिस्टम के संस्करण, डिवाइस मॉडल, अनुमानित क्षेत्र और इंस्टॉलेशन पहचानकर्ता जैसी जानकारी इकट्ठा करता है। ShiftBell अलार्म बंद करने या स्नूज़ करने, नोट सेव करने और बैकअप बनाने जैसी सुविधाओं के इस्तेमाल के रिकॉर्ड भी भेजता है।

इन रिकॉर्ड में शिफ्ट के नाम, अलार्म का समय, नोट का पाठ या शेड्यूल की दूसरी सामग्री शामिल नहीं होती। इन आंकड़ों पर Google की निजता नीति लागू होती है।

ऐप की विश्वसनीयता जांचने के लिए ShiftBell, Google Firebase Analytics को अलार्म शेड्यूल होने, शुरू होने, अपडेट होने और डिवाइस रीस्टार्ट होने की दर्ज घटनाओं की गिनती, अनुमति और बैटरी प्रतिबंधों की श्रेणियां तथा डिवाइस निर्माता की श्रेणी भेज सकता है। इन आंकड़ों में मूल डायग्नोस्टिक फाइलें, अलार्म पहचानकर्ता या समय, शेड्यूल और नोट की सामग्री शामिल नहीं होती। कुछ रिकॉर्ड अगली बार ऐप खोलने पर भेजे जाते हैं, इसलिए रिपोर्ट की तारीख घटना की तारीख से अलग हो सकती है।

### ऐप अपडेट

ऐप अपडेट की उपलब्धता Google Play से जांची जाती है।

पुराने संस्करण Firebase से सार्वजनिक अपडेट सेटिंग पढ़ सकते हैं। इस अनुरोध में शेड्यूल या नोट की सामग्री शामिल नहीं होती।

### विज्ञापन (Google AdMob)

ShiftBell में Google AdMob के बैनर विज्ञापन दिखते हैं। विज्ञापन दिखाने और उनके प्रदर्शन को मापने के लिए विज्ञापन SDK डिवाइस पहचानकर्ता, IP पते, ऐप में गतिविधि और समस्या जांच की जानकारी का उपयोग कर सकता है। ShiftBell विज्ञापन अनुरोधों में आपका शिफ्ट शेड्यूल, अलार्म का समय या नोट की सामग्री शामिल नहीं करता।

जहां Google की सहमति प्रणाली के अनुसार ज़रूरी हो, ऐप विज्ञापनों के बारे में आपकी पसंद पूछता है। उपलब्ध होने पर सेटिंग में विज्ञापन की निजता सेटिंग से अपनी पसंद देख या बदल सकते हैं। Google इस जानकारी का उपयोग कैसे करता है, यह उसकी निजता नीति में बताया गया है।

### ऐप को किन अनुमतियों की ज़रूरत है

• सूचनाएं: अलार्म की स्थिति और पहले से याद दिलाने वाली सूचना दिखाने के लिए।
• दूसरे ऐप्स के ऊपर दिखाना: दूसरे ऐप इस्तेमाल करते समय अलार्म स्क्रीन दिखाने के लिए।
• सटीक अलार्म: तय समय पर अलार्म बजाने के लिए।

Android की सेटिंग में ये अनुमतियां देख सकते हैं। अनुमति न देने पर अलार्म की सूचनाएं सीमित हो सकती हैं या अलार्म अपेक्षा के अनुसार काम नहीं कर सकते।

• लॉक स्क्रीन: फ़ोन लॉक होने पर अलार्म स्क्रीन दिखाने के लिए फ़ुल-स्क्रीन सूचनाओं की अनुमति।

### डेटा रखना और हटाना

ऐप अनइंस्टॉल करने पर उसका स्थानीय डेटाबेस हट जाता है। Download/ShiftBell में सेव बैकअप और समस्या जांच की फ़ाइलें रह सकती हैं। ज़रूरत न होने पर इन्हें फ़ाइल मैनेजर से हटाएं।

बैकअप एन्क्रिप्टेड नहीं होते। इनमें आपका पूरा स्थानीय डेटा हो सकता है। इन्हें सुरक्षित रखें। ऐप इन फ़ाइलों को अपने आप अपलोड नहीं करता। अगर आप इन्हें किसी क्लाउड सेवा पर रखते हैं या किसी को भेजते हैं, तो उस कॉपी का नियंत्रण उस सेवा या व्यक्ति के पास होगा।

ऐप खुद लिया गया एक बैकअप और अपने आप लिया गया एक बैकअप रखता है। उसी प्रकार का नया बैकअप पुराने की जगह लेता है।

इस्तेमाल के आंकड़ों और विज्ञापन डेटा को रखने पर Google की नीतियां लागू होती हैं।

ऐप के अस्थायी फ़ोल्डर में मौजूद जांच के संलग्नक ऐप अनइंस्टॉल करने पर हट जाते हैं। ईमेल या दूसरे ऐप से भेजी गई कॉपी उस सेवा और प्राप्तकर्ता के पास रहती है।

पुराने संस्करणों में बनाया गया डेटा आपके हटाने या ऐप अनइंस्टॉल करने तक डिवाइस पर रह सकता है, भले ही मौजूदा इंटरफेस में वह सुविधा उपलब्ध न हो।

डेवलपर ईमेल से मिले सहायता संदेशों, भेजने वाले के ईमेल पते और डायग्नोस्टिक अटैचमेंट का उपयोग सवालों के जवाब देने और समस्याओं की जांच के लिए करता है। इन्हें समस्या का समाधान होने के 30 दिनों के भीतर हटा दिया जाता है। lowvibe07@gmail.com पर मिले हटाने के अनुरोधों पर बिना अनावश्यक देरी के कार्रवाई की जाती है। ईमेल सेवा द्वारा अलग से रखी गई प्रतियों पर उस सेवा की नीति लागू होती है।

### बच्चों के लिए नहीं है

यह ऐप 14 साल से कम उम्र के बच्चों के लिए नहीं है। हम जानबूझकर बच्चों की निजी जानकारी इकट्ठा नहीं करते।

### संपर्क

ऐप में मदद या निजता से जुड़े सवालों के लिए:
lowvibe07@gmail.com

### कोरियाई इंटरफेस और पुराने संस्करण

कुछ सुविधाएं केवल कोरियाई इंटरफेस में उपलब्ध हैं। भाषा बदलने के बाद भी उन सुविधाओं के स्थानीय इवेंट, नींद के रिकॉर्ड और संपर्क डिवाइस पर रह सकते हैं। अपने आप नींद का अनुमान लगाने की सुविधा स्क्रीन और चार्जिंग की स्थिति केवल डिवाइस पर जांचती है।

इस इंटरफेस में या पुराने संस्करण में शेड्यूल साझा करने पर Firebase, दिखाया जाने वाला नाम और साझा शिफ्ट शेड्यूल (पैटर्न, शुरू होने की तारीख, शिफ्ट के रंग और तारीख के अनुसार बदलाव) एक अनाम पहचानकर्ता के साथ सेव करता है। कोड या लिंक वाला कोई भी व्यक्ति इसे देख सकता है। नोट, ओवरटाइम, नींद के रिकॉर्ड और अलार्म सेटिंग शामिल नहीं होते। साझा करना बंद करने पर साझा सामग्री हटाने का अनुरोध भेजा जाता है; v2 पुराने अपलोड से साझा सामग्री दोबारा बहाल होने से रोकने के लिए रोकने की स्थिति और संस्करण का न्यूनतम मेटाडेटा रख सकता है। ऑफलाइन अनुरोधों में देरी हो सकती है और डाउनलोड की गई प्रतियां वापस नहीं ली जा सकतीं। दोबारा इंस्टॉल करने से पहले साझा करना बंद करें: नया अनाम पहचानकर्ता बनने पर ऐप से पुराने साझा डेटा को हटाना संभव नहीं हो सकता। सहायता: lowvibe07@gmail.com।

कोरियाई इंटरफेस Firebase से सार्वजनिक छुट्टियों के सुधार पढ़ता है; इस अनुरोध में शेड्यूल की सामग्री शामिल नहीं होती। वेब पर साझा कैलेंडर सफलतापूर्वक खोले जाने की गिनती अलग से की जाती है; इन इवेंट में शेयर कोड या संपर्कों के नाम नहीं होते। सुविधाएं और डेटा का उपयोग इंस्टॉल किए गए संस्करण और चालू सुविधाओं पर निर्भर करते हैं; इस नीति का अर्थ यह नहीं है कि नया संस्करण पहले से उपलब्ध है।
