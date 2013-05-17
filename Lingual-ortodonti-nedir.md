Lingual ortodonti nedir ve bu tedavi nasıl yapılır?

Tüm bu soruların yanıtları aşağıdaki linkte yer alan makalede.

go to functions.php and
remove_action('genesis_footer', 'genesis_do_footer');

add this:
genesis_register_sidebar(array(
    'name'=>'Footer Left',
    'description' => 'This is the first column of the footer section.',
    'before_title'=>'<h4 class="widgettitle">','after_title'=>'</h4>'
));
genesis_register_sidebar(array(
    'name'=>'Footer Middle',
    'description' => 'This is the second column of the footer section. Half the size of The First column this section is great for lists like a blogroll widget. ',
    'before_title'=>'<h4 class="widgettitle">','after_title'=>'</h4>'
));
genesis_register_sidebar(array(
    'name'=>'Footer Right',
    'description' => 'This is the last column of the footer section.',
    'before_title'=>'<h4 class="widgettitle">','after_title'=>'</h4>'
));
genesis_register_sidebar(array(
    'name'=>'Footer Bar',
    'description' => 'This is the row for below the 3 columns.',
    'before_title'=>'<h4 class="widgettitle">','after_title'=>'</h4>'

Örneğin şu sitede: http://www.ortodonti.web.tr/lingual-ortodonti-nedir.htm
