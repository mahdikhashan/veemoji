<script>

export default /*#__PURE__*/{
  name: 'Veemoji', // vue component name
  props: {
    emoji: String
  }
};
</script>

<template>
  <div class="veemoji">
    <span :class="emoji"></span>
  </div>
</template>

<style scoped>
.ec {
  font-family: monospace;
  color: #000;
}
.hundred:before {
  content: "💯";
}
.onetwothreefour:before {
  content: "🔢";
}
.grinning:before {
  content: "😀";
}
.grimacing:before {
  content: "😬";
}
.grin:before {
  content: "😁";
}
.joy:before {
  content: "😂";
}
.rofl:before {
  content: "🤣";
}
.smiley:before {
  content: "😃";
}
.smile:before {
  content: "😄";
}
.sweat-smile:before {
  content: "😅";
}
.laughing:before {
  content: "😆";
}
.innocent:before {
  content: "😇";
}
.wink:before {
  content: "😉";
}
.blush:before {
  content: "😊";
}
.slightly-smiling-face:before {
  content: "🙂";
}
.upside-down-face:before {
  content: "🙃";
}
.yum:before {
  content: "😋";
}
.relieved:before {
  content: "😌";
}
.heart-eyes:before {
  content: "😍";
}
.kissing-heart:before {
  content: "😘";
}
.kissing:before {
  content: "😗";
}
.kissing-smiling-eyes:before {
  content: "😙";
}
.kissing-closed-eyes:before {
  content: "😚";
}
.stuck-out-tongue-winking-eye:before {
  content: "😜";
}
.stuck-out-tongue-closed-eyes:before {
  content: "😝";
}
.stuck-out-tongue:before {
  content: "😛";
}
.money-mouth-face:before {
  content: "🤑";
}
.nerd-face:before {
  content: "🤓";
}
.sunglasses:before {
  content: "😎";
}
.clown-face:before {
  content: "🤡";
}
.cowboy-hat-face:before {
  content: "🤠";
}
.hugs:before {
  content: "🤗";
}
.smirk:before {
  content: "😏";
}
.no-mouth:before {
  content: "😶";
}
.neutral-face:before {
  content: "😐";
}
.expressionless:before {
  content: "😑";
}
.unamused:before {
  content: "😒";
}
.roll-eyes:before {
  content: "🙄";
}
.thinking:before {
  content: "🤔";
}
.lying-face:before {
  content: "🤥";
}
.flushed:before {
  content: "😳";
}
.disappointed:before {
  content: "😞";
}
.worried:before {
  content: "😟";
}
.angry:before {
  content: "😠";
}
.rage:before {
  content: "😡";
}
.pensive:before {
  content: "😔";
}
.confused:before {
  content: "😕";
}
.slightly-frowning-face:before {
  content: "🙁";
}
.frowning-face:before {
  content: "☹";
}
.persevere:before {
  content: "😣";
}
.confounded:before {
  content: "😖";
}
.tired-face:before {
  content: "😫";
}
.weary:before {
  content: "😩";
}
.triumph:before {
  content: "😤";
}
.open-mouth:before {
  content: "😮";
}
.scream:before {
  content: "😱";
}
.fearful:before {
  content: "😨";
}
.cold-sweat:before {
  content: "😰";
}
.hushed:before {
  content: "😯";
}
.frowning:before {
  content: "😦";
}
.anguished:before {
  content: "😧";
}
.cry:before {
  content: "😢";
}
.disappointed-relieved:before {
  content: "😥";
}
.drooling-face:before {
  content: "🤤";
}
.sleepy:before {
  content: "😪";
}
.sweat:before {
  content: "😓";
}
.sob:before {
  content: "😭";
}
.dizzy-face:before {
  content: "😵";
}
.astonished:before {
  content: "😲";
}
.zipper-mouth-face:before {
  content: "🤐";
}
.nauseated-face:before {
  content: "🤢";
}
.sneezing-face:before {
  content: "🤧";
}
.mask:before {
  content: "😷";
}
.face-with-thermometer:before {
  content: "🤒";
}
.face-with-head-bandage:before {
  content: "🤕";
}
.sleeping:before {
  content: "😴";
}
.zzz:before {
  content: "💤";
}
.poop:before {
  content: "💩";
}
.smiling-imp:before {
  content: "😈";
}
.imp:before {
  content: "👿";
}
.japanese-ogre:before {
  content: "👹";
}
.japanese-goblin:before {
  content: "👺";
}
.skull:before {
  content: "💀";
}
.ghost:before {
  content: "👻";
}
.alien:before {
  content: "👽";
}
.robot:before {
  content: "🤖";
}
.smiley-cat:before {
  content: "😺";
}
.smile-cat:before {
  content: "😸";
}
.joy-cat:before {
  content: "😹";
}
.heart-eyes-cat:before {
  content: "😻";
}
.smirk-cat:before {
  content: "😼";
}
.kissing-cat:before {
  content: "😽";
}
.scream-cat:before {
  content: "🙀";
}
.crying-cat-face:before {
  content: "😿";
}
.pouting-cat:before {
  content: "😾";
}
.raised-hands:before {
  content: "🙌";
}
.clap:before {
  content: "👏";
}
.wave:before {
  content: "👋";
}
.call-me-hand:before {
  content: "🤙";
}
.plus1:before {
  content: "👍";
}
.-1:before {
  content: "👎";
}
.facepunch:before {
  content: "👊";
}
.fist:before {
  content: "✊";
}
.fist-left:before {
  content: "🤛";
}
.fist-right:before {
  content: "🤜";
}
.v:before {
  content: "✌";
}
.ok-hand:before {
  content: "👌";
}
.raised-hand:before {
  content: "✋";
}
.raised-back-of-hand:before {
  content: "🤚";
}
.open-hands:before {
  content: "👐";
}
.muscle:before {
  content: "💪";
}
.pray:before {
  content: "🙏";
}
.handshake:before {
  content: "🤝";
}
.point-up:before {
  content: "☝";
}
.point-up-2:before {
  content: "👆";
}
.point-down:before {
  content: "👇";
}
.point-left:before {
  content: "👈";
}
.point-right:before {
  content: "👉";
}
.fu:before {
  content: "🖕";
}
.raised-hand-with-fingers-splayed:before {
  content: "🖐";
}
.metal:before {
  content: "🤘";
}
.crossed-fingers:before {
  content: "🤞";
}
.vulcan-salute:before {
  content: "🖖";
}
.writing-hand:before {
  content: "✍";
}
.selfie:before {
  content: "🤳";
}
.nail-care:before {
  content: "💅";
}
.lips:before {
  content: "👄";
}
.tongue:before {
  content: "👅";
}
.ear:before {
  content: "👂";
}
.nose:before {
  content: "👃";
}
.eye:before {
  content: "👁";
}
.eyes:before {
  content: "👀";
}
.bust-in-silhouette:before {
  content: "👤";
}
.busts-in-silhouette:before {
  content: "👥";
}
.speaking-head:before {
  content: "🗣";
}
.baby:before {
  content: "👶";
}
.boy:before {
  content: "👦";
}
.girl:before {
  content: "👧";
}
.man:before {
  content: "👨";
}
.woman:before {
  content: "👩";
}
.blonde-man:before {
  content: "👱";
}
.older-man:before {
  content: "👴";
}
.older-woman:before {
  content: "👵";
}
.man-with-gua-pi-mao:before {
  content: "👲";
}
.man-with-turban:before {
  content: "👳";
}
.policeman:before {
  content: "👮";
}
.construction-worker-man:before {
  content: "👷";
}
.guardsman:before {
  content: "💂";
}
.male-detective:before {
  content: "🕵";
}
.mrs-claus:before {
  content: "🤶";
}
.santa:before {
  content: "🎅";
}
.angel:before {
  content: "👼";
}
.pregnant-woman:before {
  content: "🤰";
}
.princess:before {
  content: "👸";
}
.prince:before {
  content: "🤴";
}
.bride-with-veil:before {
  content: "👰";
}
.man-in-tuxedo:before {
  content: "🤵";
}
.running-man:before {
  content: "🏃";
}
.walking-man:before {
  content: "🚶";
}
.dancer:before {
  content: "💃";
}
.man-dancing:before {
  content: "🕺";
}
.dancing-women:before {
  content: "👯";
}
.couple:before {
  content: "👫";
}
.two-men-holding-hands:before {
  content: "👬";
}
.two-women-holding-hands:before {
  content: "👭";
}
.bowing-man:before {
  content: "🙇";
}
.man-facepalming:before {
  content: "🤦";
}
.woman-shrugging:before {
  content: "🤷";
}
.tipping-hand-woman:before {
  content: "💁";
}
.no-good-woman:before {
  content: "🙅";
}
.ok-woman:before {
  content: "🙆";
}
.raising-hand-woman:before {
  content: "🙋";
}
.pouting-woman:before {
  content: "🙎";
}
.frowning-woman:before {
  content: "🙍";
}
.haircut-woman:before {
  content: "💇";
}
.massage-woman:before {
  content: "💆";
}
.couple-with-heart-woman-man:before {
  content: "💑";
}
.couplekiss-man-woman:before {
  content: "💏";
}
.family-man-woman-boy:before {
  content: "👪";
}
.womans-clothes:before {
  content: "👚";
}
.tshirt:before {
  content: "👕";
}
.jeans:before {
  content: "👖";
}
.necktie:before {
  content: "👔";
}
.dress:before {
  content: "👗";
}
.bikini:before {
  content: "👙";
}
.kimono:before {
  content: "👘";
}
.lipstick:before {
  content: "💄";
}
.kiss:before {
  content: "💋";
}
.footprints:before {
  content: "👣";
}
.high-heel:before {
  content: "👠";
}
.sandal:before {
  content: "👡";
}
.boot:before {
  content: "👢";
}
.mans-shoe:before {
  content: "👞";
}
.athletic-shoe:before {
  content: "👟";
}
.womans-hat:before {
  content: "👒";
}
.tophat:before {
  content: "🎩";
}
.rescue-worker-helmet:before {
  content: "⛑";
}
.mortar-board:before {
  content: "🎓";
}
.crown:before {
  content: "👑";
}
.school-satchel:before {
  content: "🎒";
}
.pouch:before {
  content: "👝";
}
.purse:before {
  content: "👛";
}
.handbag:before {
  content: "👜";
}
.briefcase:before {
  content: "💼";
}
.eyeglasses:before {
  content: "👓";
}
.dark-sunglasses:before {
  content: "🕶";
}
.ring:before {
  content: "💍";
}
.closed-umbrella:before {
  content: "🌂";
}
.dog:before {
  content: "🐶";
}
.cat:before {
  content: "🐱";
}
.mouse:before {
  content: "🐭";
}
.hamster:before {
  content: "🐹";
}
.rabbit:before {
  content: "🐰";
}
.fox-face:before {
  content: "🦊";
}
.bear:before {
  content: "🐻";
}
.panda-face:before {
  content: "🐼";
}
.koala:before {
  content: "🐨";
}
.tiger:before {
  content: "🐯";
}
.lion:before {
  content: "🦁";
}
.cow:before {
  content: "🐮";
}
.pig:before {
  content: "🐷";
}
.pig-nose:before {
  content: "🐽";
}
.frog:before {
  content: "🐸";
}
.squid:before {
  content: "🦑";
}
.octopus:before {
  content: "🐙";
}
.shrimp:before {
  content: "🦐";
}
.monkey-face:before {
  content: "🐵";
}
.gorilla:before {
  content: "🦍";
}
.see-no-evil:before {
  content: "🙈";
}
.hear-no-evil:before {
  content: "🙉";
}
.speak-no-evil:before {
  content: "🙊";
}
.monkey:before {
  content: "🐒";
}
.chicken:before {
  content: "🐔";
}
.penguin:before {
  content: "🐧";
}
.bird:before {
  content: "🐦";
}
.baby-chick:before {
  content: "🐤";
}
.hatching-chick:before {
  content: "🐣";
}
.hatched-chick:before {
  content: "🐥";
}
.duck:before {
  content: "🦆";
}
.eagle:before {
  content: "🦅";
}
.owl:before {
  content: "🦉";
}
.bat:before {
  content: "🦇";
}
.wolf:before {
  content: "🐺";
}
.boar:before {
  content: "🐗";
}
.horse:before {
  content: "🐴";
}
.unicorn:before {
  content: "🦄";
}
.honeybee:before {
  content: "🐝";
}
.bug:before {
  content: "🐛";
}
.butterfly:before {
  content: "🦋";
}
.snail:before {
  content: "🐌";
}
.beetle:before {
  content: "🐞";
}
.ant:before {
  content: "🐜";
}
.spider:before {
  content: "🕷";
}
.scorpion:before {
  content: "🦂";
}
.crab:before {
  content: "🦀";
}
.snake:before {
  content: "🐍";
}
.lizard:before {
  content: "🦎";
}
.turtle:before {
  content: "🐢";
}
.tropical-fish:before {
  content: "🐠";
}
.fish:before {
  content: "🐟";
}
.blowfish:before {
  content: "🐡";
}
.dolphin:before {
  content: "🐬";
}
.shark:before {
  content: "🦈";
}
.whale:before {
  content: "🐳";
}
.whale2:before {
  content: "🐋";
}
.crocodile:before {
  content: "🐊";
}
.leopard:before {
  content: "🐆";
}
.tiger2:before {
  content: "🐅";
}
.water-buffalo:before {
  content: "🐃";
}
.ox:before {
  content: "🐂";
}
.cow2:before {
  content: "🐄";
}
.deer:before {
  content: "🦌";
}
.dromedary-camel:before {
  content: "🐪";
}
.camel:before {
  content: "🐫";
}
.elephant:before {
  content: "🐘";
}
.rhinoceros:before {
  content: "🦏";
}
.goat:before {
  content: "🐐";
}
.ram:before {
  content: "🐏";
}
.sheep:before {
  content: "🐑";
}
.racehorse:before {
  content: "🐎";
}
.pig2:before {
  content: "🐖";
}
.rat:before {
  content: "🐀";
}
.mouse2:before {
  content: "🐁";
}
.rooster:before {
  content: "🐓";
}
.turkey:before {
  content: "🦃";
}
.dove:before {
  content: "🕊";
}
.dog2:before {
  content: "🐕";
}
.poodle:before {
  content: "🐩";
}
.cat2:before {
  content: "🐈";
}
.rabbit2:before {
  content: "🐇";
}
.chipmunk:before {
  content: "🐿";
}
.paw-prints:before {
  content: "🐾";
}
.dragon:before {
  content: "🐉";
}
.dragon-face:before {
  content: "🐲";
}
.cactus:before {
  content: "🌵";
}
.christmas-tree:before {
  content: "🎄";
}
.evergreen-tree:before {
  content: "🌲";
}
.deciduous-tree:before {
  content: "🌳";
}
.palm-tree:before {
  content: "🌴";
}
.seedling:before {
  content: "🌱";
}
.herb:before {
  content: "🌿";
}
.shamrock:before {
  content: "☘";
}
.four-leaf-clover:before {
  content: "🍀";
}
.bamboo:before {
  content: "🎍";
}
.tanabata-tree:before {
  content: "🎋";
}
.leaves:before {
  content: "🍃";
}
.fallen-leaf:before {
  content: "🍂";
}
.maple-leaf:before {
  content: "🍁";
}
.ear-of-rice:before {
  content: "🌾";
}
.hibiscus:before {
  content: "🌺";
}
.sunflower:before {
  content: "🌻";
}
.rose:before {
  content: "🌹";
}
.wilted-flower:before {
  content: "🥀";
}
.tulip:before {
  content: "🌷";
}
.blossom:before {
  content: "🌼";
}
.cherry-blossom:before {
  content: "🌸";
}
.bouquet:before {
  content: "💐";
}
.mushroom:before {
  content: "🍄";
}
.chestnut:before {
  content: "🌰";
}
.jack-o-lantern:before {
  content: "🎃";
}
.shell:before {
  content: "🐚";
}
.spider-web:before {
  content: "🕸";
}
.earth-americas:before {
  content: "🌎";
}
.earth-africa:before {
  content: "🌍";
}
.earth-asia:before {
  content: "🌏";
}
.full-moon:before {
  content: "🌕";
}
.waning-gibbous-moon:before {
  content: "🌖";
}
.last-quarter-moon:before {
  content: "🌗";
}
.waning-crescent-moon:before {
  content: "🌘";
}
.new-moon:before {
  content: "🌑";
}
.waxing-crescent-moon:before {
  content: "🌒";
}
.first-quarter-moon:before {
  content: "🌓";
}
.waxing-gibbous-moon:before {
  content: "🌔";
}
.new-moon-with-face:before {
  content: "🌚";
}
.full-moon-with-face:before {
  content: "🌝";
}
.first-quarter-moon-with-face:before {
  content: "🌛";
}
.last-quarter-moon-with-face:before {
  content: "🌜";
}
.sun-with-face:before {
  content: "🌞";
}
.crescent-moon:before {
  content: "🌙";
}
.star:before {
  content: "⭐";
}
.star2:before {
  content: "🌟";
}
.dizzy:before {
  content: "💫";
}
.sparkles:before {
  content: "✨";
}
.comet:before {
  content: "☄";
}
.sun-behind-small-cloud:before {
  content: "🌤";
}
.partly-sunny:before {
  content: "⛅";
}
.sun-behind-large-cloud:before {
  content: "🌥";
}
.sun-behind-rain-cloud:before {
  content: "🌦";
}
.cloud-with-rain:before {
  content: "🌧";
}
.cloud-with-lightning-and-rain:before {
  content: "⛈";
}
.cloud-with-lightning:before {
  content: "🌩";
}
.zap:before {
  content: "⚡";
}
.fire:before {
  content: "🔥";
}
.boom:before {
  content: "💥";
}
.cloud-with-snow:before {
  content: "🌨";
}
.snowman:before {
  content: "⛄";
}
.snowman-with-snow:before {
  content: "☃";
}
.wind-face:before {
  content: "🌬";
}
.dash:before {
  content: "💨";
}
.tornado:before {
  content: "🌪";
}
.fog:before {
  content: "🌫";
}
.open-umbrella:before {
  content: "☂";
}
.umbrella:before {
  content: "☔";
}
.droplet:before {
  content: "💧";
}
.sweat-drops:before {
  content: "💦";
}
.ocean:before {
  content: "🌊";
}
.green-apple:before {
  content: "🍏";
}
.apple:before {
  content: "🍎";
}
.pear:before {
  content: "🍐";
}
.tangerine:before {
  content: "🍊";
}
.lemon:before {
  content: "🍋";
}
.banana:before {
  content: "🍌";
}
.watermelon:before {
  content: "🍉";
}
.grapes:before {
  content: "🍇";
}
.strawberry:before {
  content: "🍓";
}
.melon:before {
  content: "🍈";
}
.cherries:before {
  content: "🍒";
}
.peach:before {
  content: "🍑";
}
.pineapple:before {
  content: "🍍";
}
.kiwi-fruit:before {
  content: "🥝";
}
.avocado:before {
  content: "🥑";
}
.tomato:before {
  content: "🍅";
}
.eggplant:before {
  content: "🍆";
}
.cucumber:before {
  content: "🥒";
}
.carrot:before {
  content: "🥕";
}
.hot-pepper:before {
  content: "🌶";
}
.potato:before {
  content: "🥔";
}
.corn:before {
  content: "🌽";
}
.sweet-potato:before {
  content: "🍠";
}
.peanuts:before {
  content: "🥜";
}
.honey-pot:before {
  content: "🍯";
}
.croissant:before {
  content: "🥐";
}
.bread:before {
  content: "🍞";
}
.baguette-bread:before {
  content: "🥖";
}
.cheese:before {
  content: "🧀";
}
.egg:before {
  content: "🥚";
}
.bacon:before {
  content: "🥓";
}
.pancakes:before {
  content: "🥞";
}
.poultry-leg:before {
  content: "🍗";
}
.meat-on-bone:before {
  content: "🍖";
}
.fried-shrimp:before {
  content: "🍤";
}
.fried-egg:before {
  content: "🍳";
}
.hamburger:before {
  content: "🍔";
}
.fries:before {
  content: "🍟";
}
.stuffed-flatbread:before {
  content: "🥙";
}
.hotdog:before {
  content: "🌭";
}
.pizza:before {
  content: "🍕";
}
.spaghetti:before {
  content: "🍝";
}
.taco:before {
  content: "🌮";
}
.burrito:before {
  content: "🌯";
}
.green-salad:before {
  content: "🥗";
}
.shallow-pan-of-food:before {
  content: "🥘";
}
.ramen:before {
  content: "🍜";
}
.stew:before {
  content: "🍲";
}
.fish-cake:before {
  content: "🍥";
}
.sushi:before {
  content: "🍣";
}
.bento:before {
  content: "🍱";
}
.curry:before {
  content: "🍛";
}
.rice-ball:before {
  content: "🍙";
}
.rice:before {
  content: "🍚";
}
.rice-cracker:before {
  content: "🍘";
}
.oden:before {
  content: "🍢";
}
.dango:before {
  content: "🍡";
}
.shaved-ice:before {
  content: "🍧";
}
.ice-cream:before {
  content: "🍨";
}
.icecream:before {
  content: "🍦";
}
.cake:before {
  content: "🍰";
}
.birthday:before {
  content: "🎂";
}
.custard:before {
  content: "🍮";
}
.candy:before {
  content: "🍬";
}
.lollipop:before {
  content: "🍭";
}
.chocolate-bar:before {
  content: "🍫";
}
.popcorn:before {
  content: "🍿";
}
.doughnut:before {
  content: "🍩";
}
.cookie:before {
  content: "🍪";
}
.milk-glass:before {
  content: "🥛";
}
.beer:before {
  content: "🍺";
}
.beers:before {
  content: "🍻";
}
.clinking-glasses:before {
  content: "🥂";
}
.wine-glass:before {
  content: "🍷";
}
.tumbler-glass:before {
  content: "🥃";
}
.cocktail:before {
  content: "🍸";
}
.tropical-drink:before {
  content: "🍹";
}
.champagne:before {
  content: "🍾";
}
.sake:before {
  content: "🍶";
}
.tea:before {
  content: "🍵";
}
.coffee:before {
  content: "☕";
}
.baby-bottle:before {
  content: "🍼";
}
.spoon:before {
  content: "🥄";
}
.fork-and-knife:before {
  content: "🍴";
}
.plate-with-cutlery:before {
  content: "🍽";
}
.soccer:before {
  content: "⚽";
}
.basketball:before {
  content: "🏀";
}
.football:before {
  content: "🏈";
}
.baseball:before {
  content: "⚾";
}
.tennis:before {
  content: "🎾";
}
.volleyball:before {
  content: "🏐";
}
.rugby-football:before {
  content: "🏉";
}
.8ball:before {
  content: "🎱";
}
.golf:before {
  content: "⛳";
}
.golfing-man:before {
  content: "🏌";
}
.ping-pong:before {
  content: "🏓";
}
.badminton:before {
  content: "🏸";
}
.goal-net:before {
  content: "🥅";
}
.ice-hockey:before {
  content: "🏒";
}
.field-hockey:before {
  content: "🏑";
}
.cricket:before {
  content: "🏏";
}
.ski:before {
  content: "🎿";
}
.skier:before {
  content: "⛷";
}
.snowboarder:before {
  content: "🏂";
}
.person-fencing:before {
  content: "🤺";
}
.ice-skate:before {
  content: "⛸";
}
.bow-and-arrow:before {
  content: "🏹";
}
.fishing-pole-and-fish:before {
  content: "🎣";
}
.boxing-glove:before {
  content: "🥊";
}
.martial-arts-uniform:before {
  content: "🥋";
}
.rowing-man:before {
  content: "🚣";
}
.swimming-man:before {
  content: "🏊";
}
.surfing-man:before {
  content: "🏄";
}
.bath:before {
  content: "🛀";
}
.basketball-man:before {
  content: "⛹";
}
.weight-lifting-man:before {
  content: "🏋";
}
.biking-man:before {
  content: "🚴";
}
.mountain-biking-man:before {
  content: "🚵";
}
.horse-racing:before {
  content: "🏇";
}
.business-suit-levitating:before {
  content: "🕴";
}
.trophy:before {
  content: "🏆";
}
.running-shirt-with-sash:before {
  content: "🎽";
}
.medal-sports:before {
  content: "🏅";
}
.medal-military:before {
  content: "🎖";
}
.1st-place-medal:before {
  content: "🥇";
}
.2nd-place-medal:before {
  content: "🥈";
}
.3rd-place-medal:before {
  content: "🥉";
}
.reminder-ribbon:before {
  content: "🎗";
}
.rosette:before {
  content: "🏵";
}
.ticket:before {
  content: "🎫";
}
.tickets:before {
  content: "🎟";
}
.performing-arts:before {
  content: "🎭";
}
.art:before {
  content: "🎨";
}
.circus-tent:before {
  content: "🎪";
}
.microphone:before {
  content: "🎤";
}
.headphones:before {
  content: "🎧";
}
.musical-score:before {
  content: "🎼";
}
.musical-keyboard:before {
  content: "🎹";
}
.drum:before {
  content: "🥁";
}
.saxophone:before {
  content: "🎷";
}
.trumpet:before {
  content: "🎺";
}
.guitar:before {
  content: "🎸";
}
.violin:before {
  content: "🎻";
}
.clapper:before {
  content: "🎬";
}
.video-game:before {
  content: "🎮";
}
.space-invader:before {
  content: "👾";
}
.dart:before {
  content: "🎯";
}
.game-die:before {
  content: "🎲";
}
.slot-machine:before {
  content: "🎰";
}
.bowling:before {
  content: "🎳";
}
.red-car:before {
  content: "🚗";
}
.taxi:before {
  content: "🚕";
}
.blue-car:before {
  content: "🚙";
}
.bus:before {
  content: "🚌";
}
.trolleybus:before {
  content: "🚎";
}
.racing-car:before {
  content: "🏎";
}
.police-car:before {
  content: "🚓";
}
.ambulance:before {
  content: "🚑";
}
.fire-engine:before {
  content: "🚒";
}
.minibus:before {
  content: "🚐";
}
.truck:before {
  content: "🚚";
}
.articulated-lorry:before {
  content: "🚛";
}
.tractor:before {
  content: "🚜";
}
.kick-scooter:before {
  content: "🛴";
}
.motorcycle:before {
  content: "🏍";
}
.bike:before {
  content: "🚲";
}
.motor-scooter:before {
  content: "🛵";
}
.rotating-light:before {
  content: "🚨";
}
.oncoming-police-car:before {
  content: "🚔";
}
.oncoming-bus:before {
  content: "🚍";
}
.oncoming-automobile:before {
  content: "🚘";
}
.oncoming-taxi:before {
  content: "🚖";
}
.aerial-tramway:before {
  content: "🚡";
}
.mountain-cableway:before {
  content: "🚠";
}
.suspension-railway:before {
  content: "🚟";
}
.railway-car:before {
  content: "🚃";
}
.train:before {
  content: "🚋";
}
.monorail:before {
  content: "🚝";
}
.bullettrain-side:before {
  content: "🚄";
}
.bullettrain-front:before {
  content: "🚅";
}
.light-rail:before {
  content: "🚈";
}
.mountain-railway:before {
  content: "🚞";
}
.steam-locomotive:before {
  content: "🚂";
}
.train2:before {
  content: "🚆";
}
.metro:before {
  content: "🚇";
}
.tram:before {
  content: "🚊";
}
.station:before {
  content: "🚉";
}
.helicopter:before {
  content: "🚁";
}
.small-airplane:before {
  content: "🛩";
}
.flight-departure:before {
  content: "🛫";
}
.flight-arrival:before {
  content: "🛬";
}
.sailboat:before {
  content: "⛵";
}
.motor-boat:before {
  content: "🛥";
}
.speedboat:before {
  content: "🚤";
}
.ferry:before {
  content: "⛴";
}
.passenger-ship:before {
  content: "🛳";
}
.rocket:before {
  content: "🚀";
}
.artificial-satellite:before {
  content: "🛰";
}
.seat:before {
  content: "💺";
}
.canoe:before {
  content: "🛶";
}
.anchor:before {
  content: "⚓";
}
.construction:before {
  content: "🚧";
}
.fuelpump:before {
  content: "⛽";
}
.busstop:before {
  content: "🚏";
}
.vertical-traffic-light:before {
  content: "🚦";
}
.traffic-light:before {
  content: "🚥";
}
.checkered-flag:before {
  content: "🏁";
}
.ship:before {
  content: "🚢";
}
.ferris-wheel:before {
  content: "🎡";
}
.roller-coaster:before {
  content: "🎢";
}
.carousel-horse:before {
  content: "🎠";
}
.building-construction:before {
  content: "🏗";
}
.foggy:before {
  content: "🌁";
}
.tokyo-tower:before {
  content: "🗼";
}
.factory:before {
  content: "🏭";
}
.fountain:before {
  content: "⛲";
}
.rice-scene:before {
  content: "🎑";
}
.mountain:before {
  content: "⛰";
}
.mountain-snow:before {
  content: "🏔";
}
.mount-fuji:before {
  content: "🗻";
}
.volcano:before {
  content: "🌋";
}
.japan:before {
  content: "🗾";
}
.camping:before {
  content: "🏕";
}
.tent:before {
  content: "⛺";
}
.national-park:before {
  content: "🏞";
}
.motorway:before {
  content: "🛣";
}
.railway-track:before {
  content: "🛤";
}
.sunrise:before {
  content: "🌅";
}
.sunrise-over-mountains:before {
  content: "🌄";
}
.desert:before {
  content: "🏜";
}
.beach-umbrella:before {
  content: "🏖";
}
.desert-island:before {
  content: "🏝";
}
.city-sunrise:before {
  content: "🌇";
}
.city-sunset:before {
  content: "🌆";
}
.cityscape:before {
  content: "🏙";
}
.night-with-stars:before {
  content: "🌃";
}
.bridge-at-night:before {
  content: "🌉";
}
.milky-way:before {
  content: "🌌";
}
.stars:before {
  content: "🌠";
}
.sparkler:before {
  content: "🎇";
}
.fireworks:before {
  content: "🎆";
}
.rainbow:before {
  content: "🌈";
}
.houses:before {
  content: "🏘";
}
.european-castle:before {
  content: "🏰";
}
.japanese-castle:before {
  content: "🏯";
}
.stadium:before {
  content: "🏟";
}
.statue-of-liberty:before {
  content: "🗽";
}
.house:before {
  content: "🏠";
}
.house-with-garden:before {
  content: "🏡";
}
.derelict-house:before {
  content: "🏚";
}
.office:before {
  content: "🏢";
}
.department-store:before {
  content: "🏬";
}
.post-office:before {
  content: "🏣";
}
.european-post-office:before {
  content: "🏤";
}
.hospital:before {
  content: "🏥";
}
.bank:before {
  content: "🏦";
}
.hotel:before {
  content: "🏨";
}
.convenience-store:before {
  content: "🏪";
}
.school:before {
  content: "🏫";
}
.love-hotel:before {
  content: "🏩";
}
.wedding:before {
  content: "💒";
}
.classical-building:before {
  content: "🏛";
}
.church:before {
  content: "⛪";
}
.mosque:before {
  content: "🕌";
}
.synagogue:before {
  content: "🕍";
}
.kaaba:before {
  content: "🕋";
}
.shinto-shrine:before {
  content: "⛩";
}
.watch:before {
  content: "⌚";
}
.iphone:before {
  content: "📱";
}
.calling:before {
  content: "📲";
}
.computer:before {
  content: "💻";
}
.keyboard:before {
  content: "⌨";
}
.desktop-computer:before {
  content: "🖥";
}
.printer:before {
  content: "🖨";
}
.computer-mouse:before {
  content: "🖱";
}
.trackball:before {
  content: "🖲";
}
.joystick:before {
  content: "🕹";
}
.clamp:before {
  content: "🗜";
}
.minidisc:before {
  content: "💽";
}
.floppy-disk:before {
  content: "💾";
}
.cd:before {
  content: "💿";
}
.dvd:before {
  content: "📀";
}
.vhs:before {
  content: "📼";
}
.camera:before {
  content: "📷";
}
.camera-flash:before {
  content: "📸";
}
.video-camera:before {
  content: "📹";
}
.movie-camera:before {
  content: "🎥";
}
.film-projector:before {
  content: "📽";
}
.film-strip:before {
  content: "🎞";
}
.telephone-receiver:before {
  content: "📞";
}
.pager:before {
  content: "📟";
}
.fax:before {
  content: "📠";
}
.tv:before {
  content: "📺";
}
.radio:before {
  content: "📻";
}
.studio-microphone:before {
  content: "🎙";
}
.level-slider:before {
  content: "🎚";
}
.control-knobs:before {
  content: "🎛";
}
.stopwatch:before {
  content: "⏱";
}
.timer-clock:before {
  content: "⏲";
}
.alarm-clock:before {
  content: "⏰";
}
.mantelpiece-clock:before {
  content: "🕰";
}
.hourglass-flowing-sand:before {
  content: "⏳";
}
.hourglass:before {
  content: "⌛";
}
.satellite:before {
  content: "📡";
}
.battery:before {
  content: "🔋";
}
.electric-plug:before {
  content: "🔌";
}
.bulb:before {
  content: "💡";
}
.flashlight:before {
  content: "🔦";
}
.candle:before {
  content: "🕯";
}
.wastebasket:before {
  content: "🗑";
}
.oil-drum:before {
  content: "🛢";
}
.money-with-wings:before {
  content: "💸";
}
.dollar:before {
  content: "💵";
}
.yen:before {
  content: "💴";
}
.euro:before {
  content: "💶";
}
.pound:before {
  content: "💷";
}
.moneybag:before {
  content: "💰";
}
.credit-card:before {
  content: "💳";
}
.gem:before {
  content: "💎";
}
.balance-scale:before {
  content: "⚖";
}
.wrench:before {
  content: "🔧";
}
.hammer:before {
  content: "🔨";
}
.hammer-and-pick:before {
  content: "⚒";
}
.hammer-and-wrench:before {
  content: "🛠";
}
.pick:before {
  content: "⛏";
}
.nut-and-bolt:before {
  content: "🔩";
}
.gear:before {
  content: "⚙";
}
.chains:before {
  content: "⛓";
}
.gun:before {
  content: "🔫";
}
.bomb:before {
  content: "💣";
}
.hocho:before {
  content: "🔪";
}
.dagger:before {
  content: "🗡";
}
.crossed-swords:before {
  content: "⚔";
}
.shield:before {
  content: "🛡";
}
.smoking:before {
  content: "🚬";
}
.skull-and-crossbones:before {
  content: "☠";
}
.coffin:before {
  content: "⚰";
}
.funeral-urn:before {
  content: "⚱";
}
.amphora:before {
  content: "🏺";
}
.crystal-ball:before {
  content: "🔮";
}
.prayer-beads:before {
  content: "📿";
}
.barber:before {
  content: "💈";
}
.alembic:before {
  content: "⚗";
}
.telescope:before {
  content: "🔭";
}
.microscope:before {
  content: "🔬";
}
.hole:before {
  content: "🕳";
}
.pill:before {
  content: "💊";
}
.syringe:before {
  content: "💉";
}
.thermometer:before {
  content: "🌡";
}
.label:before {
  content: "🏷";
}
.bookmark:before {
  content: "🔖";
}
.toilet:before {
  content: "🚽";
}
.shower:before {
  content: "🚿";
}
.bathtub:before {
  content: "🛁";
}
.key:before {
  content: "🔑";
}
.old-key:before {
  content: "🗝";
}
.couch-and-lamp:before {
  content: "🛋";
}
.sleeping-bed:before {
  content: "🛌";
}
.bed:before {
  content: "🛏";
}
.door:before {
  content: "🚪";
}
.bellhop-bell:before {
  content: "🛎";
}
.framed-picture:before {
  content: "🖼";
}
.world-map:before {
  content: "🗺";
}
.parasol-on-ground:before {
  content: "⛱";
}
.moyai:before {
  content: "🗿";
}
.shopping:before {
  content: "🛍";
}
.shopping-cart:before {
  content: "🛒";
}
.balloon:before {
  content: "🎈";
}
.flags:before {
  content: "🎏";
}
.ribbon:before {
  content: "🎀";
}
.gift:before {
  content: "🎁";
}
.confetti-ball:before {
  content: "🎊";
}
.tada:before {
  content: "🎉";
}
.dolls:before {
  content: "🎎";
}
.wind-chime:before {
  content: "🎐";
}
.crossed-flags:before {
  content: "🎌";
}
.izakaya-lantern:before {
  content: "🏮";
}
.envelope-with-arrow:before {
  content: "📩";
}
.incoming-envelope:before {
  content: "📨";
}
.e-mail:before {
  content: "📧";
}
.love-letter:before {
  content: "💌";
}
.postbox:before {
  content: "📮";
}
.mailbox-closed:before {
  content: "📪";
}
.mailbox:before {
  content: "📫";
}
.mailbox-with-mail:before {
  content: "📬";
}
.mailbox-with-no-mail:before {
  content: "📭";
}
.package:before {
  content: "📦";
}
.postal-horn:before {
  content: "📯";
}
.inbox-tray:before {
  content: "📥";
}
.outbox-tray:before {
  content: "📤";
}
.scroll:before {
  content: "📜";
}
.page-with-curl:before {
  content: "📃";
}
.bookmark-tabs:before {
  content: "📑";
}
.bar-chart:before {
  content: "📊";
}
.chart-with-upwards-trend:before {
  content: "📈";
}
.chart-with-downwards-trend:before {
  content: "📉";
}
.page-facing-up:before {
  content: "📄";
}
.date:before {
  content: "📅";
}
.calendar:before {
  content: "📆";
}
.spiral-calendar:before {
  content: "🗓";
}
.card-index:before {
  content: "📇";
}
.card-file-box:before {
  content: "🗃";
}
.ballot-box:before {
  content: "🗳";
}
.file-cabinet:before {
  content: "🗄";
}
.clipboard:before {
  content: "📋";
}
.spiral-notepad:before {
  content: "🗒";
}
.file-folder:before {
  content: "📁";
}
.open-file-folder:before {
  content: "📂";
}
.card-index-dividers:before {
  content: "🗂";
}
.newspaper-roll:before {
  content: "🗞";
}
.newspaper:before {
  content: "📰";
}
.notebook:before {
  content: "📓";
}
.closed-book:before {
  content: "📕";
}
.green-book:before {
  content: "📗";
}
.blue-book:before {
  content: "📘";
}
.orange-book:before {
  content: "📙";
}
.notebook-with-decorative-cover:before {
  content: "📔";
}
.ledger:before {
  content: "📒";
}
.books:before {
  content: "📚";
}
.open-book:before {
  content: "📖";
}
.link:before {
  content: "🔗";
}
.paperclip:before {
  content: "📎";
}
.paperclips:before {
  content: "🖇";
}
.triangular-ruler:before {
  content: "📐";
}
.straight-ruler:before {
  content: "📏";
}
.pushpin:before {
  content: "📌";
}
.round-pushpin:before {
  content: "📍";
}
.triangular-flag-on-post:before {
  content: "🚩";
}
.white-flag:before {
  content: "🏳";
}
.black-flag:before {
  content: "🏴";
}
.closed-lock-with-key:before {
  content: "🔐";
}
.lock:before {
  content: "🔒";
}
.unlock:before {
  content: "🔓";
}
.lock-with-ink-pen:before {
  content: "🔏";
}
.pen:before {
  content: "🖊";
}
.fountain-pen:before {
  content: "🖋";
}
.memo:before {
  content: "📝";
}
.crayon:before {
  content: "🖍";
}
.paintbrush:before {
  content: "🖌";
}
.mag:before {
  content: "🔍";
}
.mag-right:before {
  content: "🔎";
}
.yellow-heart:before {
  content: "💛";
}
.green-heart:before {
  content: "💚";
}
.blue-heart:before {
  content: "💙";
}
.purple-heart:before {
  content: "💜";
}
.black-heart:before {
  content: "🖤";
}
.broken-heart:before {
  content: "💔";
}
.heavy-heart-exclamation:before {
  content: "❣";
}
.two-hearts:before {
  content: "💕";
}
.revolving-hearts:before {
  content: "💞";
}
.heartbeat:before {
  content: "💓";
}
.heartpulse:before {
  content: "💗";
}
.sparkling-heart:before {
  content: "💖";
}
.cupid:before {
  content: "💘";
}
.gift-heart:before {
  content: "💝";
}
.heart-decoration:before {
  content: "💟";
}
.peace-symbol:before {
  content: "☮";
}
.latin-cross:before {
  content: "✝";
}
.star-and-crescent:before {
  content: "☪";
}
.om:before {
  content: "🕉";
}
.wheel-of-dharma:before {
  content: "☸";
}
.star-of-david:before {
  content: "✡";
}
.six-pointed-star:before {
  content: "🔯";
}
.menorah:before {
  content: "🕎";
}
.yin-yang:before {
  content: "☯";
}
.orthodox-cross:before {
  content: "☦";
}
.place-of-worship:before {
  content: "🛐";
}
.ophiuchus:before {
  content: "⛎";
}
.aries:before {
  content: "♈";
}
.taurus:before {
  content: "♉";
}
.gemini:before {
  content: "♊";
}
.cancer:before {
  content: "♋";
}
.leo:before {
  content: "♌";
}
.virgo:before {
  content: "♍";
}
.libra:before {
  content: "♎";
}
.scorpius:before {
  content: "♏";
}
.sagittarius:before {
  content: "♐";
}
.capricorn:before {
  content: "♑";
}
.aquarius:before {
  content: "♒";
}
.pisces:before {
  content: "♓";
}
.id:before {
  content: "🆔";
}
.atom-symbol:before {
  content: "⚛";
}
.u7a7a:before {
  content: "🈳";
}
.u5272:before {
  content: "🈹";
}
.radioactive:before {
  content: "☢";
}
.biohazard:before {
  content: "☣";
}
.mobile-phone-off:before {
  content: "📴";
}
.vibration-mode:before {
  content: "📳";
}
.u6709:before {
  content: "🈶";
}
.u7121:before {
  content: "🈚";
}
.u7533:before {
  content: "🈸";
}
.u55b6:before {
  content: "🈺";
}
.vs:before {
  content: "🆚";
}
.accept:before {
  content: "🉑";
}
.white-flower:before {
  content: "💮";
}
.ideograph-advantage:before {
  content: "🉐";
}
.u5408:before {
  content: "🈴";
}
.u6e80:before {
  content: "🈵";
}
.u7981:before {
  content: "🈲";
}
.ab:before {
  content: "🆎";
}
.cl:before {
  content: "🆑";
}
.sos:before {
  content: "🆘";
}
.no-entry:before {
  content: "⛔";
}
.name-badge:before {
  content: "📛";
}
.no-entry-sign:before {
  content: "🚫";
}
.x:before {
  content: "❌";
}
.o:before {
  content: "⭕";
}
.stop-sign:before {
  content: "🛑";
}
.anger:before {
  content: "💢";
}
.no-pedestrians:before {
  content: "🚷";
}
.do-not-litter:before {
  content: "🚯";
}
.no-bicycles:before {
  content: "🚳";
}
.non-potable-water:before {
  content: "🚱";
}
.underage:before {
  content: "🔞";
}
.no-mobile-phones:before {
  content: "📵";
}
.exclamation:before {
  content: "❗";
}
.grey-exclamation:before {
  content: "❕";
}
.question:before {
  content: "❓";
}
.grey-question:before {
  content: "❔";
}
.low-brightness:before {
  content: "🔅";
}
.high-brightness:before {
  content: "🔆";
}
.trident:before {
  content: "🔱";
}
.fleur-de-lis:before {
  content: "⚜";
}
.children-crossing:before {
  content: "🚸";
}
.beginner:before {
  content: "🔰";
}
.u6307:before {
  content: "🈯";
}
.chart:before {
  content: "💹";
}
.negative-squared-cross-mark:before {
  content: "❎";
}
.white-check-mark:before {
  content: "✅";
}
.diamond-shape-with-a-dot-inside:before {
  content: "💠";
}
.cyclone:before {
  content: "🌀";
}
.loop:before {
  content: "➿";
}
.globe-with-meridians:before {
  content: "🌐";
}
.atm:before {
  content: "🏧";
}
.passport-control:before {
  content: "🛂";
}
.customs:before {
  content: "🛃";
}
.baggage-claim:before {
  content: "🛄";
}
.left-luggage:before {
  content: "🛅";
}
.wheelchair:before {
  content: "♿";
}
.no-smoking:before {
  content: "🚭";
}
.wc:before {
  content: "🚾";
}
.potable-water:before {
  content: "🚰";
}
.mens:before {
  content: "🚹";
}
.womens:before {
  content: "🚺";
}
.baby-symbol:before {
  content: "🚼";
}
.restroom:before {
  content: "🚻";
}
.put-litter-in-its-place:before {
  content: "🚮";
}
.cinema:before {
  content: "🎦";
}
.signal-strength:before {
  content: "📶";
}
.koko:before {
  content: "🈁";
}
.ng:before {
  content: "🆖";
}
.ok:before {
  content: "🆗";
}
.up:before {
  content: "🆙";
}
.cool:before {
  content: "🆒";
}
.new:before {
  content: "🆕";
}
.free:before {
  content: "🆓";
}
.keycap-ten:before {
  content: "🔟";
}
.pause-button:before {
  content: "⏸";
}
.next-track-button:before {
  content: "⏭";
}
.stop-button:before {
  content: "⏹";
}
.record-button:before {
  content: "⏺";
}
.play-or-pause-button:before {
  content: "⏯";
}
.previous-track-button:before {
  content: "⏮";
}
.fast-forward:before {
  content: "⏩";
}
.rewind:before {
  content: "⏪";
}
.twisted-rightwards-arrows:before {
  content: "🔀";
}
.repeat:before {
  content: "🔁";
}
.repeat-one:before {
  content: "🔂";
}
.arrow-up-small:before {
  content: "🔼";
}
.arrow-down-small:before {
  content: "🔽";
}
.arrow-double-up:before {
  content: "⏫";
}
.arrow-double-down:before {
  content: "⏬";
}
.arrows-counterclockwise:before {
  content: "🔄";
}
.abc:before {
  content: "🔤";
}
.abcd:before {
  content: "🔡";
}
.capital-abcd:before {
  content: "🔠";
}
.symbols:before {
  content: "🔣";
}
.musical-note:before {
  content: "🎵";
}
.notes:before {
  content: "🎶";
}
.curly-loop:before {
  content: "➰";
}
.arrows-clockwise:before {
  content: "🔃";
}
.heavy-plus-sign:before {
  content: "➕";
}
.heavy-minus-sign:before {
  content: "➖";
}
.heavy-division-sign:before {
  content: "➗";
}
.heavy-dollar-sign:before {
  content: "💲";
}
.currency-exchange:before {
  content: "💱";
}
.end:before {
  content: "🔚";
}
.back:before {
  content: "🔙";
}
.on:before {
  content: "🔛";
}
.top:before {
  content: "🔝";
}
.soon:before {
  content: "🔜";
}
.radio-button:before {
  content: "🔘";
}
.white-circle:before {
  content: "⚪";
}
.black-circle:before {
  content: "⚫";
}
.red-circle:before {
  content: "🔴";
}
.large-blue-circle:before {
  content: "🔵";
}
.small-orange-diamond:before {
  content: "🔸";
}
.small-blue-diamond:before {
  content: "🔹";
}
.large-orange-diamond:before {
  content: "🔶";
}
.large-blue-diamond:before {
  content: "🔷";
}
.small-red-triangle:before {
  content: "🔺";
}
.black-large-square:before {
  content: "⬛";
}
.white-large-square:before {
  content: "⬜";
}
.small-red-triangle-down:before {
  content: "🔻";
}
.black-medium-small-square:before {
  content: "◾";
}
.white-medium-small-square:before {
  content: "◽";
}
.black-square-button:before {
  content: "🔲";
}
.white-square-button:before {
  content: "🔳";
}
.speaker:before {
  content: "🔈";
}
.sound:before {
  content: "🔉";
}
.loud-sound:before {
  content: "🔊";
}
.mute:before {
  content: "🔇";
}
.mega:before {
  content: "📣";
}
.loudspeaker:before {
  content: "📢";
}
.bell:before {
  content: "🔔";
}
.no-bell:before {
  content: "🔕";
}
.black-joker:before {
  content: "🃏";
}
.mahjong:before {
  content: "🀄";
}
.flower-playing-cards:before {
  content: "🎴";
}
.thought-balloon:before {
  content: "💭";
}
.right-anger-bubble:before {
  content: "🗯";
}
.speech-balloon:before {
  content: "💬";
}
.left-speech-bubble:before {
  content: "🗨";
}
.clock1:before {
  content: "🕐";
}
.clock2:before {
  content: "🕑";
}
.clock3:before {
  content: "🕒";
}
.clock4:before {
  content: "🕓";
}
.clock5:before {
  content: "🕔";
}
.clock6:before {
  content: "🕕";
}
.clock7:before {
  content: "🕖";
}
.clock8:before {
  content: "🕗";
}
.clock9:before {
  content: "🕘";
}
.clock10:before {
  content: "🕙";
}
.clock11:before {
  content: "🕚";
}
.clock12:before {
  content: "🕛";
}
.clock130:before {
  content: "🕜";
}
.clock230:before {
  content: "🕝";
}
.clock330:before {
  content: "🕞";
}
.clock430:before {
  content: "🕟";
}
.clock530:before {
  content: "🕠";
}
.clock630:before {
  content: "🕡";
}
.clock730:before {
  content: "🕢";
}
.clock830:before {
  content: "🕣";
}
.clock930:before {
  content: "🕤";
}
.clock1030:before {
  content: "🕥";
}
.clock1130:before {
  content: "🕦";
}
.clock1230:before {
  content: "🕧";
}
</style>
