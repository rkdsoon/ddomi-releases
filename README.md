# ddomi

**A tiny doodle-guessing game for two, living in your Mac's menu bar.**

You draw something in a few strokes. Your buddy guesses what it is. You tell them if they got it. That is the whole game, and it fits in a sticky note.

![ddomi screens: empty state, drawing, judging, diary](images/hero.png)

## Why you might like it

- **Made for two.** One pair, one shared notepad. No feeds, no followers, no strangers.
- **Stays out of the way.** It lives in the menu bar and in a small floating sticky note. No notifications, no sounds, no Dock icon. Take a turn when you feel like it.
- **A minute a round.** Pick a word (or type your own), scribble it, send. Your buddy guesses; you say **Correct!** or **Nope!**, or reveal the answer.
- **Words in English or Korean.** Flip the `EN | 한` switch and the suggestions follow.
- **A doodle diary.** Every finished round, with the drawing, the guesses and the result, piles up for both of you.
- **Private by design.** No account, no name, no email. Each Mac gets an anonymous ID, and the only things ever stored are your doodles, guesses and results, visible to the two of you alone.

## Requirements

- macOS 14 (Sonoma) or newer
- Apple silicon or Intel Mac (one build runs on both)
- An internet connection; a buddy with a Mac

## Install

1. Open the [latest release](https://github.com/rkdsoon/ddomi-releases/releases/latest) and download `ddomi-<version>.zip`.
2. Double-click the zip. You get `ddomi.app`. Drag it into your **Applications** folder.
3. Open it. ddomi is not notarized by Apple (it is a hobby project), so macOS warns you the first time:
   - **macOS 15 or newer:** double-click the app and click **Done** on the warning. Open **System Settings → Privacy & Security**, scroll to the bottom, and click **Open Anyway** next to "ddomi". Confirm with your password or Touch ID.
   - **macOS 14:** right-click (or Control-click) `ddomi.app` in Applications and choose **Open**, then click **Open** in the dialog.
4. If macOS asks whether ddomi may use an item in your keychain, choose **Always Allow**. That is how it remembers who you are between launches.

You only do this once. From then on ddomi updates itself.

## First launch

A sticky-note window appears near the top-right corner of your screen, and a small scribble icon shows up in the menu bar.

- Drag the note by its top edge to move it. Close it with the red button when it is in the way; the app keeps running in the menu bar.
- Press **Option + Command + D** to bring the note back, or click the menu bar icon to open the same screen as a popover.
- Right-click the menu bar icon for **Show floating window**, **Check for updates…** and **Quit ddomi**.

## Pair with your buddy

You pair once.

1. One of you clicks **Create a code** and gets a 6-character code. **Copy** it and send it over any way you like.
2. The other clicks **Enter a code** and types it in.
3. Both of you see **Connected with your buddy**.

Codes expire after a day, so pair soon after creating one.

## Play

1. **New doodle.** Pick one of three suggested words, **Shuffle** for new ones, or type your own.
2. **Draw.** Three pen colors, **Undo**, **Clear**. Then **Send**.
3. **Your buddy guesses.** They see your drawing and type a guess.
4. **You judge.** **Correct!** closes the round. **Nope!** sends it back for another guess. **Reveal answer** ends it and shows the word.
5. **Got it.** The guesser taps once to clear the result, and either of you can start the next doodle.

Only one doodle is in play at a time. If you both try to send at once, the second one is kept on your canvas so you can send it next.

Open **Doodle diary** at the bottom of the note to browse past rounds.

## Updates

ddomi checks this repository for new versions a few hours after you open it and offers to install them. You can also right-click the menu bar icon and choose **Check for updates…**. Release notes live under [Releases](https://github.com/rkdsoon/ddomi-releases/releases).

## Troubleshooting

**I cannot find the menu bar icon.** Menu bar tidying apps (Hidden Bar, Bartender, Ice) often tuck new icons away, and a notch can hide them too. Press **Option + Command + D** to open the floating note; it works without the icon.

**"Open Anyway" is missing.** It only appears after you have tried to open the app once. Double-click the app again, then return to Privacy & Security.

**The keychain dialog keeps appearing.** Choose **Always Allow**, not **Allow**.

**After an update it forgot our pair.** Click **Reconnect**. It restores the pairing without a new code.

**Something else?** Open an issue in this repository.

---

## 한국어 안내

ddomi(또미)는 둘이서 하는 낙서 맞히기 게임입니다. 메뉴 막대와 작은 메모지 창에서 돌아가고, 알림·소리·Dock 아이콘이 없습니다.

**설치:** [최신 릴리스](https://github.com/rkdsoon/ddomi-releases/releases/latest)에서 `ddomi-<버전>.zip`을 받아 풀고, `ddomi.app`을 응용 프로그램 폴더에 넣습니다. 처음 열 때 경고가 뜨면 **시스템 설정 → 개인정보 보호 및 보안** 맨 아래의 **그래도 열기**를 누르세요(macOS 14는 우클릭 → 열기). 키체인 허용 창이 뜨면 **항상 허용**.

**사용:** 켜면 화면 오른쪽 위에 메모지 창이 뜹니다. 닫았다가 다시 열려면 **Option + Command + D**. 한 사람이 **Create a code**로 코드를 만들고, 다른 사람이 **Enter a code**로 입력하면 연결됩니다. 그다음은 **New doodle** → 단어 고르기(`EN | 한` 전환 가능) → 그리기 → **Send**. 상대가 추측하면 **Correct!** / **Nope!** / **Reveal answer**로 판정합니다. 지난 라운드는 **Doodle diary**에서 봅니다.

**업데이트:** 앱이 알아서 새 버전을 확인하고 설치를 제안합니다. 메뉴 막대 아이콘 우클릭 → **Check for updates…** 로 바로 확인할 수도 있습니다.

소스 코드는 별도의 비공개 저장소에 있습니다.
