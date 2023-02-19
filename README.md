# LearnQA_PythonAPI

to set up a variable on Mac OS:
export ENV=prod
check the newly set up variable:
echo $ENV


python3 -m pytest --alluredir=test_results/ tests/

python3 -m pytest tests/ 

allure serve test_results/ 