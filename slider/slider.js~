function slider_function()
{
  $('#page_section').css('display', 'none');
  $('#second_section').css('display', 'block');
} // slider fnctn endng

function modal_close_handler()
{
     $('#page_section').css('display', 'block');
     $('#second_section').css('display', 'none');
     $('#left_span').html('');
     var round_element = document.createElement('i');
     $(round_element).addClass('fa fa-circle');
     $(round_element).attr('id', 'left_circle_btn');
     var span_element = document.createElement('span');
     $(span_element).html('----------------------');
     $(span_element).attr('id', 'middle_span');
     $('#left_span').append(round_element);
     $('#left_span').append(span_element);
     $('#left_span').css('left', '0px');
} //modal closer fnctn endng


function animate_function()
{
     $('#left_span').animate({left: '250px'}, 1000, 'linear', function()
     {  
        $('#middle_span').html(' ');
        slider_function();
     });
} //animate fnctn endng