一、解锁抖音步骤：1，请在surge模组里添加TIkTokUnlock模组，https://raw.githubusercontent.com/imlzc/surge/main/module/TikTokUnlock.sgmodule
             2，添加规则集  https://raw.githubusercontent.com/imlzc/surge/main/tiktok.list ，如果默认走代理或者开全局，可不添加。
             3，以上操作完成后后如果还不能观看，请在MitM里 hostname中加上以下兩條
               -*snssdk.com, -*amemv.com
               
               
二、YouTube去视频内广告：1.在surge模组添加模块，https://raw.githubusercontent.com/imlzc/surge/main/module/YouTubeAD.sgmodule
                      2.如果没生效，请在MitM里手动添加hostname：*.googlevideo
以上均需开启MitM
