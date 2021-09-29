/**
 * Auto Cookie Clicker
 * Auto click cookies and golden cookies in the Cookie Clicker 
 * game found here: http://orteil.dashnet.org/cookieclicker/
 */


/**
 * How to in Chrome:
 * Open the browers and navigate to http://orteil.dashnet.org/cookieclicker/
 * then pressCTRL + SHIFT + J to open the developer console.  Copy and paste the
 * code between the "Auto Clicker" tags and press enter and the auto clicker will begin clicking.  To stop
 * the auto clicker, simply close your browers tab or refresh the page.
 */

/* ******************** Auto Clicker ******************** */

function clickId(id) {
  var element = document.getElementById(id);
	if(element !== undefined) {
		doEvent(element, "click");
	}
	window.setTimeout(clickId, 25, id);
}

function doEvent(element, type) {
    trigger = document.createEvent('HTMLEvents');
    trigger.initEvent(type, true, true);
    element.dispatchEvent(trigger);
}

window.setTimeout(clickId, 25, "bigCookie");
window.setTimeout(clickId, 25, "goldenCookie");

/* ****************** End Auto Clicker ****************** */

/**
 * More Cheats:
 * There are of course many ways to cheat in a javascript based game.  Simply open
 * the developer console and enter any of the following lines of code.
 */


/* Change your Mouse Cookies Per Second (MCPS) */
Game.computedMouseCps=123456789;

/* Change your Cookies Per Second (CPS) */
Game.cookiesPs=123456789

/* Spawn a Golden Cookie */
Game.goldenCookie.delay= 0;
Game.goldenCookie.life=0;
Game.goldenCookie.spawn();

/* Add cookies to your current cookie supply */
Game.cookies= Game.cookies + 1000000000;
