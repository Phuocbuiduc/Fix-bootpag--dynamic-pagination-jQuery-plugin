Apply next 5Pages:
	1.Import file nextpage.js (/js/nextpage.js)
	2.trong phần HTML, Thay file js: jquery.bootpag.min.js = nextpage.js
	3.Trong phần js của file HTML:
		 --Thay phần init pagin như phía dưới.
		 
		 // init pagin
		$(id).bootpag({
			total: totalPage,
			page: pageNum,
			maxVisible: 5,
			leaps: true,
			firstLastUse: true,
			first: '&#10094;&#10094;',
			last: '&#10095;&#10095;',
			wrapClass: 'pagination',
			activeClass: 'active',
			disabledClass: 'disabled',
			next: '&#10095;',
			prev: '&#10094;',
		});