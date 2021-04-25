# 숫자 야구 게임
## 진행 방법
* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정
* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)

## 기능 목록
#### (1) 1부터 9까지 서로 다른 수로 이루어진 3자리 수를 만든다.
* (1-1) 1부터 9까지의 수를 한개씩 가지고 있는 같은수를 포함하지 않는 변수를 만든다.
* (1-2) '1-1'에서 만든 변수에서 3가지의 수를 랜덤으로 골라 3자리 숫자를 만든다.

#### (2) 3자리의 서로다른 숫자를 입력받는다.
* (2-1) 숫자를 입력 받는다.
* (2-2) 3자리 이상일경우 실패되고 '2-1'로 돌아간다.
* (2-2) 1-9에 해당하는 숫자가 아닐경우 실패되고 '2-1'로 돌아간다.
* (2-3) 같은 숫자가 두번이상 존재하는 경우 실패되고 '2-1'로 돌아간다.

#### (3) 컴퓨터의 수와 입력받은 수가 모두 스트라이크가 될때까지 맞추며 힌트를 얻는다. (맞출때까지 반복한다.)
* (3-1) 스트라이크 갯수를 구한다. -> 컴퓨터의 수와 입력받은수의 같은 자릿수의 수가 일치한다.
* (3-2) 볼 갯수를 구한다. -> 스트라이크가 아닌 경우인 자릿수의 입력받은 수가 컴퓨터의 수에 포함된다.
* (3-3) 낫띵인지 확인한다. -> 스트라이크 갯수와 볼의 갯수가 모두 0이다.
* (3-3) 모두 스트라이크인지 확인한다. -> 스트라이크 갯수가 입력받은 수의 길이와 같다.
* (3-4) 모두 스트라이크가 아닌경우 (2) 부터 다시 실행한다.
* (3-5) 모두 스트라이크인 경우 게임종료 안내를 띄우며 게임을 새로 시작할지, 종료할지를 선택한다. -> 새로 시작하는 경우 (1)부터 다시 실행, 종료시 (4)번 실행

#### (4) 프로그램을 종료한다.
