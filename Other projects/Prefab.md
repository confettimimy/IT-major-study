## Prefab

프리팹(Prefab)은 미리 만들어 놓은 게임 오브젝트, 템플릿이다. 

프리팹은 Asset에 저장되어 있으며, 프리팹 인스턴스(Prefab Instance)를 생성하여, 월드 상에서 동작한다. 

**프리팹으로부터 원하는 만큼의 프리팹 인스턴스를 생성할 수 있다.** 생성된 프리팹 인스턴스는 서로 독립적으로 동작하며, 프리팹 인스턴스의 프로펄티를 수정해도, 다른 프리팹 인스턴스에는 영향을 주지 않는다. 

​     

## Prefab Instance

프리팹은 미리 정의된 클래스로부터 new 키워드를 통해 클래스의 인스턴스를 생성하는 것과 같은 방식으로 동작한다.

Object Class의 Instantiate(prefab) 함수를 사용해 인스턴스를 생성한다.

Object Class는 Unity Class의 최상위 클래스이다. 
