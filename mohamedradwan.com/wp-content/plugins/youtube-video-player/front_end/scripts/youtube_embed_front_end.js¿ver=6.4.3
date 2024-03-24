var loc_this= new Array()
function onYouTubeIframeAPIReady(){	
  jQuery('.youtube_embed_iframe').each(function(index, element) {  			
		loc_this[index]=element;
        var player = new YT.Player(element, {
          events: {
            'onReady':  set_initial_values 
           /* 'onStateChange': onPlayerStateChange*/
          }
        });	
		function set_initial_values(event){			
				if(jQuery(loc_this[index]).attr('data-volume')){					
					player.setVolume(jQuery(loc_this[index]).attr('data-volume'));
				}
			}	
    });	
}
function disable_player_autoplay_in_iframes(){
	jQuery('body').find('iframe[date-autoplay=1]').each(function(){jQuery(this).attr('src',jQuery(this).attr('src').replace('autoplay=1','autoplay=0'))});
}
jQuery(document).ready(function(e) {
    jQuery('.youtube_embed_thickbox').on('click',function(){
		var iframe_set_autoplay=jQuery(this).find('iframe[date-autoplay=1]');
		if(iframe_set_autoplay){
			iframe_set_autoplay=iframe_set_autoplay.eq(0)
			jQuery(iframe_set_autoplay).attr('src',jQuery(iframe_set_autoplay).attr('src').replace('autoplay=0','autoplay=1'))
		}
		tb_remove=function() {
		jQuery("#TB_imageOff").unbind("click");
		jQuery("#TB_closeWindowButton").unbind("click");
		jQuery("#TB_window").fadeOut("fast",function(){jQuery('#TB_window,#TB_overlay,#TB_HideSelect').trigger("tb_unload").unbind().remove();});
		jQuery( 'body' ).removeClass( 'modal-open' );
		jQuery("#TB_load").remove();
		if (typeof document.body.style.maxHeight == "undefined") {//if IE 6
			jQuery("body","html").css({height: "auto", width: "auto"});
			jQuery("html").css("overflow","");
		}
		jQuery(document).unbind('.thickbox');
		disable_player_autoplay_in_iframes();
		return false;
	}
	});
	
	
	
});
