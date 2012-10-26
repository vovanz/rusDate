rusDate
=======

Вспомогательный класс для русской версии функции date (Yii)

Использование:
- поместить папку rusDate в папку extensions
- configuration. Add to config:

	    'components' => array(
	    	//.......................
	        'rusDate' => array(
	            'class' => 'ext.rusDate.CRusDate'
	        )
			//....................
		),
				