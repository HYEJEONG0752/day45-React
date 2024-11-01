# **Day 45 문제**

# **쉬운 문제 (15개)**

## **상태(state)란 무엇인가요?**
- 상태(state)는 컴포넌트가 동적으로 데이터를 관리하기 위해 사용하는 객체입니다.
컴포넌트의 상태가 변경되면 React는 해당 컴포넌트를 다시 렌더링하여 UI를 업데이트합니다.

## **속성(props)의 주요 용도는 무엇인가요?**
- 속성(props)은 부모 컴포넌트가 자식 컴포넌트에 데이터를 전달하기 위해 사용하는 읽기 전용 객체입니다. 자식 컴포넌트에서 속성 값을 수정할 수는 없으며, 재사용성과 구성 가능성을 높이는데 사용됩니다.

## **React에서 상태(state)를 선언할 때 사용하는 훅은 무엇인가요?**
- `useState` 훅을 사용하여 함수형 컴포넌트에서 상태를 선언합니다.

## **부모 컴포넌트에서 자식 컴포넌트로 데이터를 전달할 때 사용하는 것은 무엇인가요?**
- 속성(props)을 사용하여 데이터를 전달합니다.

## **상태(state)를 업데이트하는 함수는 무엇이라고 하나요?**
- 상태를 업데이트하는 함수는 `setState`입니다. `useState`훅을 사용할 경우, `setState`와 같은 이름을 직접 정의할 수 있습니다.

## **속성(props)은 변경 가능한가요?**
- 아니요, 속성(props)은 읽기 전용이므로 컴포넌트 내부에서 수정할 수 없습니다.

## **함수형 컴포넌트에서 상태(state)를 선언하려면 어떤 함수를 사용해야 하나요?**
- `useState` 함수를 사용하여 상태를 선언합니다. 

## **React에서 단방향 데이터 흐름이란 무엇을 의미하나요?**
- 단방향 데이터 흐름이란 데이터가 부모 컴포넌트에서 자식 컴포넌트로만 전달되는 방식을 의미합니다.
자식 컴포넌트는 부모로 데이터를 직접 전송할 수 없으며, 부모가 자식을 통해 데이터 흐름을 제어합니다. 

## **상태(state)와 속성(props)의 가장 큰 차이점은 무엇인가요?**
- 상태(state)는 컴포넌트 내부에서 관리되며 변경할 수 있는 데이터입니다. 속성(props)은 부모 컴포넌트로부터 전달받으며 읽기 전용입니다.

## **컴포넌트가 다시 렌더링되는 주요 원인은 무엇인가요?**
- 컴포넌트가 다시 렌더링되는 주요 원인은 상태(state)나 속성(props)이 변경될 때입니다.

## **상태(state)를 변경할 때 직접 수정해도 되나요?**
- 아니요, 상태(state)를 직접 수정해서는 안 됩니다. 상태를 변경할 때는 `setState` 함수를 사용해야 합니다.

## **속성(props)을 통해 전달된 데이터를 자식 컴포넌트에서 수정할 수 있나요?**
- 아니요, 속성(props)은 읽기 전용이므로 자식 컴포넌트에서 수정할 수 없습니다.

### **상태(state)와 속성(props) 중 어떤 것이 컴포넌트 내부에서 관리되나요?**
- 상태(state)

## **상태(state)의 초기값을 설정하는 방법은 무엇인가요?**
- `useState` 훅을 사용하여 상태를 선언할 때, 초기값을 매개변수로 전달하여 설정할 수 있습니다. 
```javascript
const [count, setCount] = useState(0);
```

## **부모 컴포넌트에서 자식 컴포넌트로 함수를 전달할 수 있나요?**
- 네, 부모 컴포넌트에서 자식 컴포넌트로 함수를 속성(props)을 통해 전달할 수 있습니다. 자식 컴포넌트는 이 함수를 호출하여 부모 컴포넌트와 상호작용할 수 있습니다.