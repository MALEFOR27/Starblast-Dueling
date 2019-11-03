# Starblast-Dueling

// Starblast Dueling v2.1

var switch_button = {
  id: "switch",
  position: [66,1,2.5,4],
  clickable: true,
  shortcut: "V",
  visible: true,
  components: [
    { type:  "box",position:[0,0,100,100],fill:"rgba(68, 85, 102, 0)",stroke:"rgba(204, 221, 238, 0.667)",width:2},
    { type: "text",position:[10,23,80,30],value:"SWITCH",color:"rgba(204, 221, 238, 0.8)"},
    { type: "text",position:[10,45,80,23],value:"SHIP",color:"rgba(204, 221, 238, 0.8)"},
    { type: "text",position:[20,70,60,20],value:"[V]",color:"rgba(204, 221, 238, 0.8)"}
    ]
};

var stats_button = {
  id: "stats",
  position: [69,1,2.5,4],
  clickable: true,
  shortcut: "B",
  visible: true,
  components: [
    { type:  "box",position:[0,0,100,100],fill:"rgba(68, 85, 102, 0)",stroke:"rgba(204, 221, 238, 0.667)",width:2},
    { type: "text",position:[10,23,80,30],value:"TOGGLE",color:"rgba(204, 221, 238, 0.8)"},
    { type: "text",position:[10,45,80,23],value:"STATS",color:"rgba(204, 221, 238, 0.8)"},
    { type: "text",position:[20,70,60,20],value:"[B]",color:"rgba(204, 221, 238, 0.8)"}
    ]
};

var reset_button = {
  id: "reset",
  position: [72,1,2.5,4],
  clickable: true,
  shortcut: "R",
  visible: true,
  components: [
    { type:  "box",position:[0,0,100,100],fill:"rgba(68, 85, 102, 0)",stroke:"rgba(204, 221, 238, 0.667)",width:2},
    { type: "text",position:[10,34,80,25],value:"RESET",color:"rgba(204, 221, 238, 0.8)"},
    { type: "text",position:[20,70,60,20],value:"[R]",color:"rgba(204, 221, 238, 0.8)"}
    ]
};

var crystals_button = {
  id: "crystals",
  position: [75,1,2.5,4],
  clickable: true,
  shortcut: "M",
  visible: true,
  components: [
    { type:  "box",position:[0,0,100,100],fill:"rgba(68, 85, 102, 0)",stroke:"rgba(204, 221, 238, 0.667)",width:2},
    { type: "text",position:[10,34,80,25],value:"CRYSTALS",color:"rgba(204, 221, 238, 0.8)"},
    { type: "text",position:[20,70,60,20],value:"[M]",color:"rgba(204, 221, 238, 0.8)"}
    ]
};

var god_button = {
  id: "admin",
  position: [],
  clickable: true,
  shortcut: "Z",
  visible: true,
  components: []
};

var buttons = [stats_button, reset_button, switch_button, crystals_button];

var AdminToolPrecision_791 = '{"name":"AdminToolPrecision","level":7.9,"model":1,"size":1,"zoom":0.7,"specs":{"shield":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"generator":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"ship":{"mass":1e+300,"speed":[800,800],"rotation":[1e+300,1e+300],"acceleration":[1e+300,1e+300]}},"bodies":{"object0":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0,0],"y":[-30,-30,0,0],"z":[0,0,0,0]},"width":[0,5,5,0],"height":[0,5,5,0],"texture":[4],"angle":0,"laser":{"damage":[1055,1055],"rate":10,"speed":[400,400],"number":1}}},"typespec":{"name":"AdminToolPrecision","level":7.9,"model":1,"code":791,"specs":{"shield":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"generator":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"ship":{"mass":1e+300,"speed":[800,800],"rotation":[1e+300,1e+300],"acceleration":[1e+300,1e+300]}},"shape":[0.601,0.604,0.373,0.227,0.166,0.129,0.11,0.097,0.085,0.079,0.075,0.073,0.071,0.071,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0.071,0.073,0.075,0.079,0.085,0.097,0.11,0.129,0.166,0.227,0.373,0.604],"lasers":[{"x":0,"y":-0.6,"z":0,"angle":0,"damage":[1055,1055],"rate":10,"speed":[400,400],"number":1,"spread":0,"error":0,"recoil":0}],"radius":0.604}}';
var AdminToolLocal_792 = '{"name":"AdminToolLocal","level":7.9,"model":2,"size":1,"zoom":0.7,"specs":{"shield":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"generator":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"ship":{"mass":1e+300,"speed":[800,800],"rotation":[1e+300,1e+300],"acceleration":[1e+300,1e+300]}},"bodies":{"object0":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":0,"texture":4,"laser":{"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"angle":324,"error":0,"recoil":0}},"object1":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":45,"texture":4,"laser":{"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"angle":324,"error":0,"recoil":0}},"object2":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":90,"texture":4,"laser":{"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"angle":324,"error":0,"recoil":0}},"object3":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":135,"texture":4,"laser":{"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"angle":324,"error":0,"recoil":0}},"object4":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":180,"texture":4,"laser":{"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"angle":324,"error":0,"recoil":0}},"object5":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":225,"texture":4,"laser":{"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"angle":324,"error":0,"recoil":0}},"object6":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":270,"texture":4,"laser":{"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"angle":324,"error":0,"recoil":0}},"object7":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":315,"texture":4,"laser":{"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"angle":324,"error":0,"recoil":0}}},"typespec":{"name":"AdminToolLocal","level":7.9,"model":2,"code":792,"specs":{"shield":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"generator":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"ship":{"mass":1e+300,"speed":[800,800],"rotation":[1e+300,1e+300],"acceleration":[1e+300,1e+300]}},"shape":[1,0.737,0.373,0.227,0.32,0.651,1,0.848,0.45,0.25,0.279,0.562,0.996,1,0.562,0.279,0.25,0.45,0.848,1,0.651,0.32,0.227,0.373,0.737,1,0.737,0.373,0.227,0.32,0.651,1,0.848,0.45,0.25,0.279,0.562,0.996,1,0.562,0.279,0.25,0.45,0.848,1,0.651,0.32,0.227,0.373,0.737],"lasers":[{"x":0,"y":-1,"z":0,"angle":0,"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"spread":324,"error":0,"recoil":0},{"x":-0.707,"y":-0.707,"z":0,"angle":45,"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"spread":324,"error":0,"recoil":0},{"x":-1,"y":0,"z":0,"angle":90,"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"spread":324,"error":0,"recoil":0},{"x":-0.707,"y":0.707,"z":0,"angle":135,"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"spread":324,"error":0,"recoil":0},{"x":0,"y":1,"z":0,"angle":180,"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"spread":324,"error":0,"recoil":0},{"x":0.707,"y":0.707,"z":0,"angle":225,"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"spread":324,"error":0,"recoil":0},{"x":1,"y":0,"z":0,"angle":270,"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"spread":324,"error":0,"recoil":0},{"x":0.707,"y":-0.707,"z":0,"angle":315,"damage":[1055,1055],"rate":10,"speed":[500,500],"number":10,"spread":324,"error":0,"recoil":0}],"radius":1}}';
var AdminToolGlobal_793 = '{"name":"AdminToolGlobal","level":7.9,"model":3,"size":1,"zoom":0.7,"specs":{"shield":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"generator":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"ship":{"mass":1e+300,"speed":[800,800],"rotation":[1e+300,1e+300],"acceleration":[1e+300,1e+300]}},"bodies":{"object0":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":0,"texture":17,"laser":{"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"angle":324,"error":0,"recoil":20000}},"object1":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":45,"texture":17,"laser":{"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"angle":324,"error":0,"recoil":20000}},"object2":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":90,"texture":17,"laser":{"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"angle":324,"error":0,"recoil":20000}},"object3":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":135,"texture":17,"laser":{"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"angle":324,"error":0,"recoil":20000}},"object4":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":180,"texture":17,"laser":{"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"angle":324,"error":0,"recoil":20000}},"object5":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":225,"texture":17,"laser":{"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"angle":324,"error":0,"recoil":20000}},"object6":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":270,"texture":17,"laser":{"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"angle":324,"error":0,"recoil":20000}},"object7":{"section_segments":[45,135,225,315],"offset":{"x":0,"y":0,"z":0},"position":{"x":[0,0,0],"y":[-50,-30,0],"z":[0,0,0]},"width":[0,5,5],"height":[0,5,5],"angle":315,"texture":17,"laser":{"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"angle":324,"error":0,"recoil":20000}}},"typespec":{"name":"AdminToolGlobal","level":7.9,"model":3,"code":793,"specs":{"shield":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"generator":{"capacity":[1e+300,1e+300],"reload":[1e+300,1e+300]},"ship":{"mass":1e+300,"speed":[800,800],"rotation":[1e+300,1e+300],"acceleration":[1e+300,1e+300]}},"shape":[1,0.737,0.373,0.227,0.32,0.651,1,0.848,0.45,0.25,0.279,0.562,0.996,1,0.562,0.279,0.25,0.45,0.848,1,0.651,0.32,0.227,0.373,0.737,1,0.737,0.373,0.227,0.32,0.651,1,0.848,0.45,0.25,0.279,0.562,0.996,1,0.562,0.279,0.25,0.45,0.848,1,0.651,0.32,0.227,0.373,0.737],"lasers":[{"x":0,"y":-1,"z":0,"angle":0,"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"spread":324,"error":0,"recoil":20000},{"x":-0.707,"y":-0.707,"z":0,"angle":45,"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"spread":324,"error":0,"recoil":20000},{"x":-1,"y":0,"z":0,"angle":90,"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"spread":324,"error":0,"recoil":20000},{"x":-0.707,"y":0.707,"z":0,"angle":135,"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"spread":324,"error":0,"recoil":20000},{"x":0,"y":1,"z":0,"angle":180,"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"spread":324,"error":0,"recoil":20000},{"x":0.707,"y":0.707,"z":0,"angle":225,"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"spread":324,"error":0,"recoil":20000},{"x":1,"y":0,"z":0,"angle":270,"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"spread":324,"error":0,"recoil":20000},{"x":0.707,"y":-0.707,"z":0,"angle":315,"damage":[1055,1055],"rate":10,"speed":[1,1],"number":10,"spread":324,"error":0,"recoil":20000}],"radius":1}}';

var adminTools = [
  
  AdminToolPrecision_791,
  AdminToolLocal_792,
  AdminToolGlobal_793,
  
  ];

var ship_list = [
  [101,201,202,301,302,303,304,401,402,403,404,405,406,501,502,503,504,505,506,507,601,602,603,604,605,606,607,608,701,702,703,704],
  [791,792,793],
];

var vocabulary = [
    { text: "You", icon:"\u004e", key:"O" },
    { text: "GG", icon:"\u00a3", key:"G" },
    { text: "Sorry", icon:"\u00a1", key:"S" },
    { text: "No Problem", icon:"\u0047", key:"P" },
    { text: "hmm?", icon:"\u004b", key:"Q" },
    { text: "Wait", icon:"\u0048", key:"T" },
    { text: "Yes", icon:"\u004c", key:"Y" },
    { text: "No", icon:"\u004d", key:"N" },
    { text: "Attack", icon:"\u00b4", key:"A" },
    { text: "Heal", icon:"\u0037", key:"H" },
    { text: "I'm Dueling", icon:"\u00be", key:"D" },
    { text: "Idiot", icon:"\u0079", key:"I" },
    { text: "Thanks", icon:"\u0041", key:"X" },
    { text: "Kill", icon:"\u005b", key:"K" },
    { text: "Follow", icon:"\u0050", key:"F" },
    { text: "Me", icon:"\u004f", key:"E" },
    { text: "Leave", icon:"\u00b3", key:"L" },
  ] ;

this.options = {
  map_name: "Dueling v2.1", 
  root_mode: "",
  ships: adminTools,
  reset_tree: false,
  max_players: 60,
  vocabulary: vocabulary,
  lives: 5,
  map_size: 70,
  custom_map: [],
  crystal_value: 0,
  asteroids_strength: 3,
  survival_level: 8,
  starting_ship: 800, //infinit lives
  speed_mod: 1.2,

} ;

log = function(s){
game.modding.terminal.echo(s);
};
playerList = function(){
for(nn=0;nn<game.ships.length;nn++)
log(nn+" - "+game.ships[nn].name);
} ;

playerID = function() {
for (ship of game.ships) echo(ship.id + " : " + ship.name);
};

setAll = function() {
for (ship of game.ships) ship.set({type:101, shield:50000});
};

instructorSaysAll = function(saysWhat, instructor = "Zoltar"){
    for(ship of game.ships) ship.instructorSays(saysWhat, instructor);
};

hideInstructor = function(){
    for(ship of game.ships) ship.hideInstructor();
};

kick = function(ID, reason){
  game.findShip(ID).gameover({"kicked for":reason});
};
this.tick = function(game) {
  if ( game.step % 30 == 0 ) {
    for (let ship of game.ships) {
      if (!ship.custom.buttons_installed && ship.alive)
      {
        ship.custom.buttons_installed = true;
        for (b in buttons)
        {
          ship.setUIComponent(buttons[b]);
          ship.custom.tree = 0;
          for (let tree = 0; tree < ship_list.length; tree++) {
            if (ship_list[tree].indexOf(ship.type) >= 0) {
              ship.custom.tree = tree;
              break;
            }
          }
        }
      }
      var level = Math.trunc(ship.type / 100);
      if (level < 7) {
        var max_stats = 11111111 * level;
        if (ship.custom.keep_maxed) {
          if (ship.stats != max_stats) {
            ship.set({stats:max_stats});
          }
        }
      } else if (ship.stats > 0) {
        ship.set({stats:0});
      }
    }
    for ( var a = 0 ; a < game.ships.length ; a++ ) {
      var admin = game.ships[0];
      if(!admin.custom.god_button_installed) {
        admin.custom.god_button_installed = true;
        admin.setUIComponent(god_button);
      }
    }
  }
};


this.event = function(event, game) {
  switch (event.name)
  {
    case "ship_destroyed":
      if (event.killer != null)
      {
        event.killer.custom.kills = event.killer.custom.kills + 1 || 1;
      }
      break;
    case "ui_component_clicked":
      var ship = event.ship;
      var component = event.id;
      switch (component)
      {
        case "switch":
          var tree = ship.custom.tree;
          var index = -1;
          index = ship_list[tree].indexOf(ship.type);
          if (index >= 0) {
            var new_type;
            var new_stats = 0;
            index = (index + 1) % ship_list[tree].length;
            new_type = ship_list[tree][index];
            var level = Math.trunc(new_type / 100);
            if (level < 7 && ship.custom.keep_maxed)
            {
              var max = 11111111 * level;
              if (ship.stats != max) {
                new_stats = max;
              }
            }
            ship.set({type:new_type,stats:new_stats,shield:999});
          }
          break;
        case "stats":
          var stats = ship.stats;
          var level = Math.trunc(ship.type / 100);
          var max = 11111111 * level;
          if (level < 7)
          {
            if (stats == max)
            {
              ship.custom.keep_maxed = false;
              ship.set({stats:0});
            } else {
              ship.custom.keep_maxed = true;
              ship.set({stats:max});
            }
          }
          break;
        case "reset":
          var new_stats = ship.custom.keep_maxed ? 11111111 : 0;
          ship.set({type:101,stats:new_stats});
          break;
        case "crystals":
          var level = Math.trunc(ship.type / 100);
          var cargo = 980;
          switch (level) {
            case 1:
              cargo = 20;
              break;
            case 2:
              cargo = 80;
              break;
            case 3:
              cargo = 180;
              break;
            case 4:
              cargo = 320;
              break;
            case 5:
              cargo = 500;
              break;
            case 6:
              cargo = 720;
              break;
            case 7:
              cargo = 980;
              break;
          }
          ship.set({crystals:cargo,shield:999});
          break;
        case "admin":
          var new_type;
          if (ship.type == 791) {
            new_type = 792;
          } else if (ship.type == 792) {
            new_type = 793;
          } else if (ship.type == 793) {
            new_type = 791;
          } else {
            new_type = 791;
          }
          ship.set({type:new_type});
          break;
      }
      break;
  }
};
