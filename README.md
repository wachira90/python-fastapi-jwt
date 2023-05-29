# python-fastapi-jwt

python fastapi jsonwebtoken

python 3.7.4

## clone 

```sh
git clone https://github.com/wachira90/python-fastapi-jwt.git
```

## install package

```sh
cd python-fastapi-jwt/
virtualenv env
env\Scripts\activate
pip install -r req.txt
OR
pip install "fastapi[all]"
pip install "uvicorn[standard]"
pip install "python-jose[cryptography]" "passlib[bcrypt]" python-multipart
```

## run

```sh
uvicorn main:app --reload
```
