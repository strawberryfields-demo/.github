# 참고
> 현재 백엔드가 오류로 배포되지 않고 있습니다.
따라서 설치하여 확인하실 수 있습니다. 죄송합니다.

# [Notion](https://www.notion.so/nakyoungs/30e636e79873462091dac204db9c1882)
개발 기간동안의 기능 구현 개발기, 트러블 슈팅 등을 확인하실 수 있습니다.

# 프론트엔드
## project clone
```
git clone https://github.com/strawberryfields-demo/frontend.git
```
## project start
```
// FRONTEND 폴더기준
cd ./strawberry-demo-fe
npm install
// dev로 열어야 현재 백엔드와 통신이 가능합니다 (5173 포트 기준)
npm run dev
```

# 백엔드
## project clone
```
git clone https://github.com/strawberryfields-demo/backend.git
```
## project start
```
// BACKEND 폴더 기준 (윈도우입니다)
python -m pip install virtualenv
python -m venv venv
venv/Scripts/activate
pip install -r requirements.txt
cd ./strawberry_be
python manage.py runserver
```

