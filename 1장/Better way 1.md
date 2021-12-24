### 사용 중인 파이썬의 버전을 알자



##### 버전 알기
###### <pre><code>python --version</code></pre> 또는 <pre><code>python3 --version</code></pre>

##### sys 모듈 안의 값을 조사해서 런타임에 사용중인 파이썬 버전을 알아낼 수도 있다.
###### <pre><code>import(sys)</code></pre>
###### <pre><code>print(sys.version_info)</code></pre>
###### <pre><code>print(sys.version)</code></pre>
##### 핵심 정리
###### 파이썬의 주요 버전인 파이썬 2,3 모두 활발히 활용된다.
###### 파이썬에는 CPython, Jython, IronPython, PyPy같은 런타임이 있다.
###### 시스템에서 파이썬을 실행하는 명령이 사용하고자 하는 파이썬 버전인지 확인해야 한다.
###### 파이썬 커뮤니티에서 주로 다루는 버전은 파이썬 3이므로 새 파이썬 프로젝트를 시작할 때는 파이썬 3을 사용하는 것이 좋다.
