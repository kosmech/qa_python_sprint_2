# qa_python
# тест на добавление двух книг
test_add_new_book_two_books_added_books
# тест на добавление уже добавленной ранее книги
test_add_new_book_existing_book_not_added
# тест на установку рейтинга добавленной книги
test_set_book_rating_new_value_in_range_1_to_10_set_new_rating
# тест на установку рейтинга выше 10
test_set_book_rating_new_value_not_in_range_1_to_10_not_set_new_rating
# тест на проверку стандартного рейтинга добавленной книги
test_get_book_rating_name_book_shows_rating_1
# тест на вывод списка с определённым рейтингом
test_get_books_with_specific_rating_value_in_range_1_to_10_show_list
# тест на вывод путого списка при запросе рейтинга 11
test_get_books_with_specific_rating_value_not_in_range_1_to_10_show_empty_list
# тест на получение всего словаря с книгами и рейтингом
test_get_books_rating_show_dict
# тест добавление книги в избранное из добавленных раньше
test_add_book_in_favorites_book_from_books_rating_add_book_in_favorites
# тест добавление новой книги сразу в избранное
test_add_book_in_favorites_book_not_from_books_rating_not_add_book_in_favorites
# тест на удаление книги из избранного
test_delete_book_from_favorites_book_from_favorites_book_not_in_favorites