　ライフサイクルとは、まずマウントして初期化され、次にレンダリングされた後、 何らかのきっかけで再レンダリングされ、最後にアンマウントされるまでの過程。  

ライフサイクルメソッド  
	1 Mountingフェーズ: コンポーネントが初期化され、仮想DOMにマウントされる	　        までのフェーズ。ここで初めてレンダリングされる。   

	2 Updatingフェーズ: 差分検出処理エンジンが変更を検知してコンポーネント
	  が再レンダリングされる。  

	3 Unmountingフェーズ: コンポーネントが仮想DOMから削除される。  

	4 ErrorHandlingフェーズ: 子孫コンポーネントのエラーを検知補足する。   

-2の「変更を検知して再レンダリング」は基本的に２つある。propsもしくはstateの変更  
