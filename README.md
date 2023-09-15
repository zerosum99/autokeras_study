# autokeras_study


# 선택 사항일 수 있지만 일반적으로 권장되는 python_3라는 이름의 가상환경 생성 
conda create --name autokeras python=3.9 
conda activate autokeras


# Install AutoKeras
- AutoKeras only support Python 3. If you followed previous steps to use virtualenv to install tensorflow,
- you can just activate the virtualenv and use the following command to install AutoKeras.


pip install git+https://github.com/keras-team/keras-tuner.git
pip install autokeras

- If you did not use virtualenv, and you use python3 command to execute your python program,
- please use the following command to install AutoKeras.


python3 -m pip install git+https://github.com/keras-team/keras-tuner.git
python3 -m pip install autokeras