<h1> 20243093 김창현 오픈sw 과제 </h1>

<h2> top  [옵션] </h2>

<p>-b : 배치모드로 정보를 출력한다. 실시간 상화 대화형모드로 정보를 화면에 일렬로 출력한다.</p>
<p>-d delay : 지정한 시간(delay 초)의 간격으로 정보를 업데이트하여 출력한다.</p>
<p>-i idle : 토글값이 off일 때, idle 프로세스나 좀비 프로세스 정보를 출력하지 않는다.</p>
<p>-n num : 지정한 시간(num)만큼 업데이트 정보를 출력한다.</p>
<p>-p pid : 지정한 프로세스 ID(pid)의 정보만을 출력한다.</p>
<p>-q : 시간의 간격 없이 계속하여 업데이트 정보를 출력한다.</p>
<p>-s : 몇 개의 대화식 명령을 비활성화한다(시큐어 모드).</p>
<p>-S : 누적된 정보를 출력한다(cumulative 모드).</p>
<hr>
<h2> ps [옵션] </h2>
<p>
전체 프로세스와 관련된 옵션<br>
 -A : 모든 프로세스를 출력한다.<br>
	
-N : -A 옵션과 비슷하나 프로세스를 제외하고 출력한다.<br>
	
-a: 세션 리더 및 터미널에 속하지 않는 프로세스를 제외하고 출력한다.<br>
	
-d : 세션 리더를 제외한 모든 프로세스를 출력한다.<br>
	
-e : 커널 프로세스를 제외한 모든 프로세스를 출력한다.
</p>

<p>
T : 현재 터미널에서의 모든 프로세스를 출력한다.<br>
	
a : 현재 터미널의 사용자 고유 프로세스를 출력한다.<br>
	
r : 현재 실행 중인 프로세스를 출력한다.<br>
	
x : 터미널이 없는 프로세스를 출력한다.<br>
	
--deselect : -N 옵션과 같다.
</p>

<hr>
<h2> jobs [옵션] </h2>
<p>-l : 프로세스 그룹 ID를 state 필드 앞에 출력한다.</p>
<p>-n : 프로세스 그룹 중에 대표 프로세스 ID를 출력한다.</p>
<p>-p : 각 프로세스 ID에 대해 한 행씩 출력한다.</p>
<p>command : 지정한 명령어를 실행한다.</p>

<hr>
<h2> kill [시그널] </h2>
<p>pid ··· : 종료시킬 프로세스 ID나 프로세스 이름을 지정한다.</p>
<p>-s : 전달할 시그널의 종류를 지정한다. 여기에는 시그널 이름이나 번호를 써준다.</p>
<p>-l : 시그널로 사용할 수 있는 시그널 이름들을 보여준다. 이것은 /usr/include/linux/signal.h 파일에서도 알 수 있다.</p>
<p>-1, : -HUP 프로세스를 재활성화한다.</p>
<p>-9 : 프로세스를 강제로 종료시킨다.</p>

<img src="https://github.com/changPR/20243093/assets/117575062/34915e68-e92a-4165-ac74-54a236236a25" alt="예시"></img>

