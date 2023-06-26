# Ers-GiftBox

                        Giftbox System [Stater Pack]
        Free, open source starter gift box using the QBCore Framework





Installation
*Download ZIP
*Drag and drop into [standalone]
*Restart your serve

qb-core > shared > main.lua > Paste to QBShared.StarterItems table

    ['giftbox'] = { amount = 1, item = 'giftbox' },


qb-inventory > html > images

	--Ers Starter Gift Box
	['giftbox']             		= {['name'] = 'giftbox',                		['label'] = 'Starter Gift Box',       	['weight'] = 0,         ['type'] = 'item',      ['image'] = 'giftbox.png',     		    ['unique'] = true,      ['useable'] = true,     ['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'A Present with various items'},
