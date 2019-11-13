# myfistBOT
def bot(name,age,question):
	print('Вас зовут:', name)
	print('Вам уже', str(age), 'лет', ',круто!')
	print('Вашего создателя я не знаю, но мой создатель великий Шамиль! Славо ему вечное!')
start_bot = input('Хотите запустить бота?(напишите ДА или НЕТ)'+' ')  	
if start_bot == 'ДА' or start_bot == 'Да' or start_bot == 'да':
	bot(input('Как вас зовут?'+' '),input('Сколько вам лет?'+' '),input('Задайте мне вопрос:'+' '))
elif start_bot == 'НЕТ' or start_bot == 'Нет' or start_bot == 'нет':
	print('Хорошо, запуск бота отменен!')
