<template>
  <div class="ymain">
    <div class="yhead flex jus">
      <a class="yheadleft" href="#">
        <img src="../assets/sparks-orange.svg" alt="" />
      </a>
      <div class="yheadcenter flex">
        <a
          @click="qhtable('0')"
          :class="ytable == '0' ? 'yheadcenteract' : ''"
          href="#Sparks"
          >Sparks</a
        >
        <a
          @click="qhtable('1')"
          :class="ytable == '1' ? 'yheadcenteract' : ''"
          href="#members"
          >Members</a
        >
        <a
          @click="qhtable('2')"
          :class="ytable == '2' ? 'yheadcenteract' : ''"
          href="#network"
          >Network</a
        >
        <a
          @click="qhtable('3')"
          :class="ytable == '3' ? 'yheadcenteract' : ''"
          href="#apply"
          >Apply</a
        >
        <a
          @click="qhtable('4')"
          :class="ytable == '4' ? 'yheadcenteract' : ''"
          href="#faq"
          >FAQ</a
        >
        <a
          @click="qhtable('5')"
          :class="ytable == '5' ? 'yheadcenteract' : ''"
          href="#team"
          >TEAM</a
        >
      </div>
      <div class="yheadright flex">
        <div class="yheadry flex">
          <a target="_blank" href="https://discord.com/invite/lifebeyond"
            ><svg
              aria-hidden="true"
              focusable="false"
              data-prefix="fab"
              data-icon="discord"
              class="svg-inline--fa fa-discord w-[22px] text-white"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 640 512"
            >
              <path
                fill="currentColor"
                d="M524.531,69.836a1.5,1.5,0,0,0-.764-.7A485.065,485.065,0,0,0,404.081,32.03a1.816,1.816,0,0,0-1.923.91,337.461,337.461,0,0,0-14.9,30.6,447.848,447.848,0,0,0-134.426,0,309.541,309.541,0,0,0-15.135-30.6,1.89,1.89,0,0,0-1.924-.91A483.689,483.689,0,0,0,116.085,69.137a1.712,1.712,0,0,0-.788.676C39.068,183.651,18.186,294.69,28.43,404.354a2.016,2.016,0,0,0,.765,1.375A487.666,487.666,0,0,0,176.02,479.918a1.9,1.9,0,0,0,2.063-.676A348.2,348.2,0,0,0,208.12,430.4a1.86,1.86,0,0,0-1.019-2.588,321.173,321.173,0,0,1-45.868-21.853,1.885,1.885,0,0,1-.185-3.126c3.082-2.309,6.166-4.711,9.109-7.137a1.819,1.819,0,0,1,1.9-.256c96.229,43.917,200.41,43.917,295.5,0a1.812,1.812,0,0,1,1.924.233c2.944,2.426,6.027,4.851,9.132,7.16a1.884,1.884,0,0,1-.162,3.126,301.407,301.407,0,0,1-45.89,21.83,1.875,1.875,0,0,0-1,2.611,391.055,391.055,0,0,0,30.014,48.815,1.864,1.864,0,0,0,2.063.7A486.048,486.048,0,0,0,610.7,405.729a1.882,1.882,0,0,0,.765-1.352C623.729,277.594,590.933,167.465,524.531,69.836ZM222.491,337.58c-28.972,0-52.844-26.587-52.844-59.239S193.056,219.1,222.491,219.1c29.665,0,53.306,26.82,52.843,59.239C275.334,310.993,251.924,337.58,222.491,337.58Zm195.38,0c-28.971,0-52.843-26.587-52.843-59.239S388.437,219.1,417.871,219.1c29.667,0,53.307,26.82,52.844,59.239C470.715,310.993,447.538,337.58,417.871,337.58Z"
              ></path></svg
          ></a>
          <a target="_blank" href="https://twitter.com/sparksordinals"
            ><svg
              aria-hidden="true"
              focusable="false"
              data-prefix="fab"
              data-icon="x-twitter"
              class="svg-inline--fa fa-x-twitter w-[22px] text-white"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
            >
              <path
                fill="currentColor"
                d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z"
              ></path></svg
          ></a>
        </div>
        <a href="#apply"> Become a Spark </a>
      </div>
    </div>
    <div class="yone">
      <div class="yonebox flex">
        <img src="../assets/frame1288-v0.png" alt="" />
        <div class="_particles_kz2ni_16" aria-hidden="true" role="presentation">
          <div class="_particleContainer_kz2ni_21 _particleContainer1_kz2ni_29">
            <div class="_particleLayer_kz2ni_25 _particleLayer1_kz2ni_54"></div>
          </div>
          <div class="_particleContainer_kz2ni_21 _particleContainer2_kz2ni_34">
            <div class="_particleLayer_kz2ni_25 _particleLayer2_kz2ni_59"></div>
          </div>
          <div class="_particleContainer_kz2ni_21 _particleContainer3_kz2ni_39">
            <div class="_particleLayer_kz2ni_25 _particleLayer3_kz2ni_64"></div>
          </div>
          <div class="_particleContainer_kz2ni_21 _particleContainer4_kz2ni_44">
            <div class="_particleLayer_kz2ni_25 _particleLayer4_kz2ni_69"></div>
          </div>
          <div class="_particleContainer_kz2ni_21 _particleContainer5_kz2ni_49">
            <div class="_particleLayer_kz2ni_25 _particleLayer5_kz2ni_74"></div>
          </div>
        </div>
        <h1>Sparks</h1>
      </div>
    </div>
    <div class="ytwo" id="Sparks">
      <div class="ytwobox flex">
        <div class="ytwobimg flex">
          <img src="../assets/sparks-orange.svg" alt="" />
        </div>
        <div class="ytwobright flex">
          <div class="ytwobrtop flex">
            <h2>Ignite your journey</h2>
            <p>
              Darewise Entertainment, an Animoca Brands Company, is building the
              first token-based metaverse on Bitcoin.
            </p>
            <p>
              This is your chance to join the early exclusive community on
              ordinals for founders, content creators, investors, and community
              members, building together on Bitcoin and beyond.
            </p>
            <a href="#apply">Become a Spark Member Now</a>
          </div>
          <div class="ytwobrbot flex">
            <div class="ytwobrbytxt">Proudly powered by</div>
            <div class="ytwobrimgs flex">
              <img src="../assets/darewise.png" alt="" />
              <img src="../assets/animoca-brands.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="ythree" id="members">
      <div class="ythreebox flex">
        <h2>Members</h2>
        <div class="ythreebtxt">Join our curated group of Sparks members</div>
        <div class="ythreeblist">
          <div v-for="item in ythrtab" :key="item" class="ythreeblibox flex">
            <div class="ythreebliboxleft">
              <img src="../assets/frame1288-v0.png" alt="" />
            </div>
            <div class="ythreebliboxright flex">
              <div class="ythreeblbry">{{ item }}</div>
              <div class="ythreeblbrt">To be revealed soon...</div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="yfour" id="network">
      <div class="yfimgs flex">
        <div class="yfimgbg"></div>
        <img src="../assets/frame1288-v0.png" alt="" />
        <img src="../assets/frame1288-v0.png" alt="" />
        <img src="../assets/frame1288-v0.png" alt="" />
        <img src="../assets/frame1288-v0.png" alt="" />
        <img src="../assets/frame1288-v0.png" alt="" />
        <img src="../assets/frame1288-v0.png" alt="" />
        <img src="../assets/frame1288-v0.png" alt="" />
        <img src="../assets/frame1288-v0.png" alt="" />
        <img src="../assets/frame1288-v0.png" alt="" />
        <img src="../assets/frame1288-v0.png" alt="" />
        <img src="../assets/frame1288-v0.png" alt="" />
      </div>
      <div class="yfourbox">
        <div class="yfourtxtcon">
          <div class="yfourtoptit flex">
            <h2>Sparks Network Benefits</h2>
            <div>Understand and access the Sparks Network Benefits</div>
          </div>
          <div class="yfourbotbox flex">
            <div class="yfourbbleft flex">
              <div class="yfourbbleftbox flex">
                <img src="../assets/frame.svg" alt="" />
                <div>
                  Full exclusive access to the Darewise x Life Beyond Ecosystem
                  team to co-develop and build together.
                </div>
              </div>
              <div class="yfourbbleftbox flex">
                <img src="../assets/frame1.svg" alt="" />
                <div>
                  A fast track for token grants, development, and marketing
                  support for partners and builders.
                </div>
              </div>
              <div class="yfourbbleftbox flex">
                <img src="../assets/frame2.svg" alt="" />
                <div>IRL networking and partnership access.</div>
              </div>
            </div>
            <div class="yfourbbcenter">
              <img src="../assets/sparks-white.png" alt="" />
            </div>
            <div class="yfourbbleft flex">
              <div class="yfourbbleftbox flex">
                <img src="../assets/frame3.svg" alt="" />
                <div>
                  Free claim for Life Beyond lands, tokens or special events to
                  match the value of your Sparks Mint and more.
                </div>
              </div>
              <div class="yfourbbleftbox flex">
                <img src="../assets/frame4.svg" alt="" />
                <div>
                  Quarterly 1-1 calls to assess how the network can help for
                  funding, partnering, technology by Sparks Curator.
                </div>
              </div>
              <div class="yfourbbleftbox flex">
                <img src="../assets/frame5.svg" alt="" />
                <div>
                  Quarterly video conferences to tap on business leaders like
                  Yat Siu
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="yfive" id="apply">
      <div class="yfivebox">
        <div class="yfivebtxt flex">
          <div class="yfivebtxty">
            Your
            <span>SPARKS Cube Ordinal</span>
            will be your key to the network
          </div>
          <h2>Applications are closed</h2>
          <div class="yfivebtxtt">Total applicants:</div>
          <div class="yfivebtxtt yfivebtxtse">12973</div>
          <div class="yfivebtxtthr">Thanks for your overwhelming support!</div>
        </div>
      </div>
      <div class="yfivebbot flex">
        <div class="yfivebbotleft">
          <img src="../assets/frame1288-v0.png" alt="" />
        </div>
        <div class="yfivebbotright">
          <div class="yfivebbrighty flex">
            <div class="yfivebbrtxty">Applications are under review</div>
            <div class="yfivebbrtxtr">
              The next steps will be announced soon on our social media
              channels.
            </div>
          </div>
          <div class="yfivebbrightt flex">
            <div class="yfivebbrightty">Be part of our community now.</div>
            <div class="yfivebbrighttt flex">
              <a
                href="https://discord.gg/lifebeyond"
                target="_blank"
                rel="noreferrer nofollow"
                ><svg
                  aria-hidden="true"
                  focusable="false"
                  data-prefix="fab"
                  data-icon="discord"
                  class="svg-inline--fa fa-discord h-[30px] w-[30px] text-white"
                  role="img"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 640 512"
                >
                  <path
                    fill="currentColor"
                    d="M524.531,69.836a1.5,1.5,0,0,0-.764-.7A485.065,485.065,0,0,0,404.081,32.03a1.816,1.816,0,0,0-1.923.91,337.461,337.461,0,0,0-14.9,30.6,447.848,447.848,0,0,0-134.426,0,309.541,309.541,0,0,0-15.135-30.6,1.89,1.89,0,0,0-1.924-.91A483.689,483.689,0,0,0,116.085,69.137a1.712,1.712,0,0,0-.788.676C39.068,183.651,18.186,294.69,28.43,404.354a2.016,2.016,0,0,0,.765,1.375A487.666,487.666,0,0,0,176.02,479.918a1.9,1.9,0,0,0,2.063-.676A348.2,348.2,0,0,0,208.12,430.4a1.86,1.86,0,0,0-1.019-2.588,321.173,321.173,0,0,1-45.868-21.853,1.885,1.885,0,0,1-.185-3.126c3.082-2.309,6.166-4.711,9.109-7.137a1.819,1.819,0,0,1,1.9-.256c96.229,43.917,200.41,43.917,295.5,0a1.812,1.812,0,0,1,1.924.233c2.944,2.426,6.027,4.851,9.132,7.16a1.884,1.884,0,0,1-.162,3.126,301.407,301.407,0,0,1-45.89,21.83,1.875,1.875,0,0,0-1,2.611,391.055,391.055,0,0,0,30.014,48.815,1.864,1.864,0,0,0,2.063.7A486.048,486.048,0,0,0,610.7,405.729a1.882,1.882,0,0,0,.765-1.352C623.729,277.594,590.933,167.465,524.531,69.836ZM222.491,337.58c-28.972,0-52.844-26.587-52.844-59.239S193.056,219.1,222.491,219.1c29.665,0,53.306,26.82,52.843,59.239C275.334,310.993,251.924,337.58,222.491,337.58Zm195.38,0c-28.971,0-52.843-26.587-52.843-59.239S388.437,219.1,417.871,219.1c29.667,0,53.307,26.82,52.844,59.239C470.715,310.993,447.538,337.58,417.871,337.58Z"
                  ></path></svg
                ><span>Discord</span></a
              >
              <a
                href="https://twitter.com/sparksordinals"
                target="_blank"
                rel="noreferrer nofollow"
                ><svg
                  aria-hidden="true"
                  focusable="false"
                  data-prefix="fab"
                  data-icon="x-twitter"
                  class="svg-inline--fa fa-x-twitter h-[22px] w-[22px] text-white"
                  role="img"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 512 512"
                >
                  <path
                    fill="currentColor"
                    d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z"
                  ></path></svg
                ><span>X</span></a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="ysix" id="faq">
      <div class="ysixbox flex">
        <h2>Frequently Asked Questions</h2>
        <div class="ysixboxlist flex">
          <div class="ysixblbox">
            <div class="ysixblboxtxt flex">
              <div class="ysixblbtleft"></div>
              <div class="ysixblbtright">
                <div class="ysixblbtry">What chain will this NFT be on?</div>
                <div class="ysixblbtrt">
                  The Sparks collection will be inscribed on the Bitcoin
                  blockchain using the Ordinal protocol.
                </div>
              </div>
            </div>
          </div>
          <div class="ysixblbox">
            <div class="ysixblboxtxt flex">
              <div class="ysixblbtleft"></div>
              <div class="ysixblbtright">
                <div class="ysixblbtry">What chain will this NFT be on?</div>
                <div class="ysixblbtrt flex">
                  <div>
                    The Sparks collection will be inscribed on the Bitcoin
                    blockchain using the Ordinal protocol.
                  </div>
                  <div>
                    This makes Bitcoin Ordinals ideal for use as non-fungible
                    tokens (NFTs).
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="ysixblbox">
            <div class="ysixblboxtxt flex">
              <div class="ysixblbtleft"></div>
              <div class="ysixblbtright">
                <div class="ysixblbtry">What chain will this NFT be on?</div>
                <div class="ysixblbtrt flex">
                  <div>
                    Sparks is a new initiative from Darewise in its mission to
                    build the metaverse ecosystem on Bitcoin. Life Beyond will
                    be a flagship destination of that ecosystem and the Sparks
                    community an exclusive and privileged group in that
                    ecosystem.
                  </div>
                  <div>
                    Sparks will also have a chance to interact and build on Life
                    Beyond in the future.
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="ysixblbox">
            <div class="ysixblboxtxt flex">
              <div class="ysixblbtleft"></div>
              <div class="ysixblbtright">
                <div class="ysixblbtry">What chain will this NFT be on?</div>
                <div class="ysixblbtrt">
                  There is no pre-determined mint date. Mint will occur when all
                  the spots are filled. Price is 0.02btc.
                </div>
              </div>
            </div>
          </div>
          <div class="ysixblbox">
            <div class="ysixblboxtxt flex">
              <div class="ysixblbtleft"></div>
              <div class="ysixblbtright">
                <div class="ysixblbtry">What chain will this NFT be on?</div>
                <div class="ysixblbtrt flex">
                  <div>
                    The Founder’s key collection is a Polygon-based NFT
                    collection specifically for the early supporters of the Life
                    Beyond game project.
                  </div>
                  <div>
                    While the FK will remain a key part of our ecosystem and
                    community within the flagship project of Darewise, the
                    Sparks community aims at gathering the builders of the
                    larger metaverse ecosystem on Bitcoin.
                  </div>
                  <div>
                    Both community are not exclusive of each other and will
                    support each other.
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="yqi" id="team">
      <div class="yqibox">
        <h2>
          The Team behind
          <span>Sparks</span>
        </h2>
        <div class="yqilist">
          <div class="yqilistbox flex">
            <div class="yqilistbleft">
              <img src="../assets/image19.png" alt="" />
            </div>
            <div class="yqilistbright flex">
              <div class="yqilistbrighty flex" style="flex-direction: column">
                <div class="yqilistbrightyy">Ben Charbit</div>
                <div class="yqilistbrightyt">CEO - Darewise</div>
              </div>
              <div class="yqilistbrighty flex">
                <a
                  href="https://twitter.com/Ben_Charbit"
                  target="_blank"
                  rel="nofollow noreferrer"
                  ><svg
                    aria-hidden="true"
                    focusable="false"
                    data-prefix="fab"
                    data-icon="x-twitter"
                    class="svg-inline--fa fa-x-twitter w-[18px] text-white"
                    role="img"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                  >
                    <path
                      fill="currentColor"
                      d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z"
                    ></path></svg
                ></a>
                <a
                  href="https://www.linkedin.com/in/benjamin-charbit/"
                  target="_blank"
                  rel="nofollow noreferrer"
                  ><svg
                    aria-hidden="true"
                    focusable="false"
                    data-prefix="fab"
                    data-icon="linkedin"
                    class="svg-inline--fa fa-linkedin w-[18px] text-white"
                    role="img"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 448 512"
                  >
                    <path
                      fill="currentColor"
                      d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z"
                    ></path></svg
                ></a>
              </div>
            </div>
          </div>
          <div class="yqilistbox flex">
            <div class="yqilistbleft">
              <img src="../assets/image20.png" alt="" />
            </div>
            <div class="yqilistbright flex">
              <div class="yqilistbrighty flex" style="flex-direction: column">
                <div class="yqilistbrightyy">Vincent Marty</div>
                <div class="yqilistbrightyt">CPO - Darewise</div>
              </div>
              <div class="yqilistbrighty flex">
                <a
                  href="https://twitter.com/vincemarty"
                  target="_blank"
                  rel="nofollow noreferrer"
                  ><svg
                    aria-hidden="true"
                    focusable="false"
                    data-prefix="fab"
                    data-icon="x-twitter"
                    class="svg-inline--fa fa-x-twitter w-[18px] text-white"
                    role="img"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                  >
                    <path
                      fill="currentColor"
                      d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z"
                    ></path></svg
                ></a>
                <a
                  href="https://www.linkedin.com/in/vincemarty/"
                  target="_blank"
                  rel="nofollow noreferrer"
                  ><svg
                    aria-hidden="true"
                    focusable="false"
                    data-prefix="fab"
                    data-icon="linkedin"
                    class="svg-inline--fa fa-linkedin w-[18px] text-white"
                    role="img"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 448 512"
                  >
                    <path
                      fill="currentColor"
                      d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z"
                    ></path></svg
                ></a>
              </div>
            </div>
          </div>
          <div class="yqilistbox flex">
            <div class="yqilistbleft">
              <img src="../assets/image21.png" alt="" />
            </div>
            <div class="yqilistbright flex">
              <div class="yqilistbrighty flex" style="flex-direction: column">
                <div class="yqilistbrightyy">Timothée Semelin</div>
                <div class="yqilistbrightyt">Ecosystem Director - Darewise</div>
              </div>
              <div class="yqilistbrighty flex">
                <a
                  href="https://twitter.com/timweb3_"
                  target="_blank"
                  rel="nofollow noreferrer"
                  ><svg
                    aria-hidden="true"
                    focusable="false"
                    data-prefix="fab"
                    data-icon="x-twitter"
                    class="svg-inline--fa fa-x-twitter w-[18px] text-white"
                    role="img"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                  >
                    <path
                      fill="currentColor"
                      d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z"
                    ></path></svg
                ></a>
                <a
                  href="https://www.linkedin.com/in/timsemelin/"
                  target="_blank"
                  rel="nofollow noreferrer"
                  ><svg
                    aria-hidden="true"
                    focusable="false"
                    data-prefix="fab"
                    data-icon="linkedin"
                    class="svg-inline--fa fa-linkedin w-[18px] text-white"
                    role="img"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 448 512"
                  >
                    <path
                      fill="currentColor"
                      d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z"
                    ></path></svg
                ></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="yfoot flex">
      <div class="yfootimgs flex jus">
        <a
          href="https://www.animocabrands.com/"
          target="_blank"
          rel="nofollow noreferrer"
          ><img src="../assets/animoca-brands.png" alt="Animoca Brands"
        /></a>
        <a
          href="https://darewise.com/"
          target="_blank"
          rel="nofollow noreferrer"
          ><img src="../assets/darewise.png" alt="Darewise"
        /></a>
        <a
          href="https://www.lifebeyondstudios.com/"
          target="_blank"
          rel="nofollow noreferrer"
          ><img src="../assets/life-beyond.png" alt="Life Beyond"
        /></a>
      </div>
      <div class="yfootimgsy flex">
        <img src="../assets/sparks-orange.svg" alt="" />
        <div>All rights reserved © Darewise - 2023</div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";

let ytable = ref("0");
let ythrtab = ref([
  "Sparks 1",
  "Sparks 2",
  "Sparks 3",
  "Sparks 4",
  "Sparks 5",
  "Sparks 6",
]);
let qhtable = (str) => {
  ytable.value = str;
};
</script>

<style scoped>
.yhead {
  width: calc(100vw - 6rem);
  position: fixed;
  top: 3rem;
  left: 3rem;
  background: transparent;
  align-items: center;
  z-index: 100;
}
.yheadleft {
  width: 3rem;
}
.yheadleft > img {
  width: 100%;
}
.yheadcenter {
  align-items: center;
  justify-content: center;
  height: 3.75rem;
  border-radius: 120px;
  border: 1px solid #ffffff26;
  border-width: 1px;
  background-color: #07080899;
  padding-left: 5px;
  padding-right: 5px;
  box-sizing: border-box;
  margin-left: 15rem;
}
.yheadcenter a {
  position: relative;
  display: flex;
  height: 3.1875rem;
  align-items: center;
  justify-content: center;
  border: 1px solid transparent;
  padding-left: 1.25rem;
  padding-right: 1.25rem;
  font-weight: 500;
  text-transform: uppercase;
  color: #fff6;
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 0.5s;
}
.yheadcenter > a:hover {
  border-radius: 3.25rem;
  color: white;
  border-color: #ffffff1a;
  background-image: linear-gradient(
    167deg,
    rgba(255, 255, 255, 0.15) 9.09%,
    rgba(255, 255, 255, 0.05) 143.99%
  );
}
.yheadcenter .yheadcenteract {
  border-radius: 3.25rem;
  color: white;
  border-color: #ffffff1a;
  background-image: linear-gradient(
    167deg,
    rgba(255, 255, 255, 0.15) 9.09%,
    rgba(255, 255, 255, 0.05) 143.99%
  );
}
.yheadright {
  gap: 1.25rem;
  align-items: center;
  justify-content: flex-end;
}
.yheadry {
  gap: 0.75rem;
  justify-content: flex-end;
  align-items: center;
}
.yheadry > a {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 2.625rem;
  height: 2.625rem;
  border: 1px solid #ffffff26;
  border-radius: 5px;
  background-color: #ffffff0d;
  transition: all 0.15s linear;
  box-sizing: border-box;
}
.yheadry > a:hover {
  background-color: #ffffff1a;
}
.yheadry > a > svg {
  width: 1.375rem;
  color: white;
}
.yheadright > a {
  background-color: rgb(252 199 97);
  outline-width: 0px;
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 0.3s;
  box-shadow: inset calc(17 * 10px) 0 calc(17 * 5px) calc(17 * -5px) #ea5922;
  text-shadow: 0 1px 3px rgba(0, 0, 0, 0.5);
  padding-left: 1rem;
  padding-right: 1rem;
  display: flex;
  height: 2.625rem;
  width: -moz-fit-content;
  width: fit-content;
  align-items: center;
  border-radius: 5px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 600;
  text-transform: uppercase;
  color: rgb(255 255 255);
}
.yheadright > a:hover {
  scale: 1.05;
  box-shadow: inset 0 14 calc(14 * 2 / 3) calc(14 * -2 / 3) #ea5922;
  animation: 5s ease-out 0.3s infinite alternate _flicker_1cnj0_1;
}
@keyframes _flicker_1cnj0_1 {
  0% {
    filter: brightness(100%);
  }
  4% {
    filter: brightness(105%);
  }
  8% {
    filter: brightness(95%);
  }
  10% {
    filter: brightness(110%);
  }
  13% {
    filter: brightness(100%);
  }
  18% {
    filter: brightness(103%);
  }
  22% {
    filter: brightness(98%);
  }
  29% {
    filter: brightness(108%);
  }
  36% {
    filter: brightness(100%);
  }
  39% {
    filter: brightness(105%);
  }
  42% {
    filter: brightness(97%);
  }
  50% {
    filter: brightness(106%);
  }
  53% {
    filter: brightness(100%);
  }
  58% {
    filter: brightness(105%);
  }
  63% {
    filter: brightness(95%);
  }
  66% {
    filter: brightness(110%);
  }
  70% {
    filter: brightness(100%);
  }
  75% {
    filter: brightness(103%);
  }
  79% {
    filter: brightness(98%);
  }
  83% {
    filter: brightness(108%);
  }
  88% {
    filter: brightness(100%);
  }
  93% {
    filter: brightness(105%);
  }
  97% {
    filter: brightness(97%);
  }
  100% {
    filter: brightness(106%);
  }
}
.yone {
  position: relative;
  z-index: 0;
  display: flex;
  height: 100vh;
  width: 100%;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}
.yonebox {
  height: 100vh;
  width: 100%;
  justify-content: center;
  align-items: center;
  position: relative;
}
.yonebox > img {
  object-fit: cover;
  margin: 14vh auto;
  z-index: -20;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  max-width: 100%;
  height: auto;
}
._particles_kz2ni_16 {
  position: absolute;
  z-index: -5;
  height: 100vh;
  width: 100%;
  -webkit-mask-image: linear-gradient(
    -180deg,
    transparent 0,
    rgba(0, 0, 0, 0.8) 30%,
    rgba(0, 0, 0, 0.8) 70%,
    transparent 100%
  );
  mask-image: linear-gradient(
    -180deg,
    transparent 0,
    rgba(0, 0, 0, 0.8) 30%,
    rgba(0, 0, 0, 0.8) 70%,
    transparent 100%
  );
  --animDelay: -5s;
}
._particleContainer_kz2ni_21 {
  position: absolute;
  height: 8192px;
  width: 16384px;
  animation: _embersLateral_kz2ni_1 5s ease-in-out -5s infinite alternate;
}
@keyframes _embersLateral_kz2ni_1 {
  0% {
    transform: translate(-512px);
  }
  100% {
    transform: translate(-650px);
  }
}
._particleContainer2_kz2ni_34 {
  animation: _embersLateral_kz2ni_2 11s ease-in-out -5s infinite alternate;
}
@keyframes _embersLateral_kz2ni_2 {
  0% {
    transform: translate(-1300px);
  }
  100% {
    transform: translate(-1500px);
  }
}
._particleContainer3_kz2ni_39 {
  animation: _embersLateral_kz2ni_3 7s ease-in-out -5s infinite alternate;
}
@keyframes _embersLateral_kz2ni_3 {
  0% {
    transform: translate(-600px);
  }
  100% {
    transform: translate(-650px);
  }
}
._particleContainer4_kz2ni_44 {
  animation: _embersLateral_kz2ni_4 13s ease-in-out -5s infinite alternate;
}
@keyframes _embersLateral_kz2ni_4 {
  0% {
    transform: translate(-1300px);
  }
  100% {
    transform: translate(-1500px);
  }
}
._particleContainer5_kz2ni_49 {
  animation: _embersLateral_kz2ni_2 17s ease-in-out -5s infinite alternate;
}
@keyframes _embersLateral_kz2ni_2 {
  0% {
    transform: translate(-200px);
  }
  100% {
    transform: translate(-700px);
  }
}
._particleLayer_kz2ni_25 {
  position: absolute;
  height: 8192px;
  width: 16384px;
  background-image: url("../assets/embers.png");
  background-repeat: repeat;
  animation: _embers_kz2ni_1 42s linear -5s infinite;
}
@keyframes _embers_kz2ni_1 {
  0% {
    transform: translateY(-1000px);
    filter: brightness(2) hue-rotate(0deg);
  }
  50% {
    filter: brightness(2) hue-rotate(0deg);
  }
  60% {
    filter: brightness(2.5) hue-rotate(10deg);
  }
  65% {
    filter: brightness(1.2) hue-rotate(-5deg);
  }
  80% {
    filter: brightness(5) hue-rotate(0deg);
  }
  100% {
    transform: translateY(-3048px);
    filter: brightness(2) hue-rotate(0deg);
  }
}
._particleLayer4_kz2ni_69 {
  animation: _embers_kz2ni_1 37s linear -5s infinite;
}
._particleLayer3_kz2ni_64 {
  animation: _embers_kz2ni_1 15s linear -5s infinite;
}
._particleLayer2_kz2ni_59 {
  animation: _embers_kz2ni_2 50s linear -5s infinite;
}
@keyframes _embers_kz2ni_2 {
  0% {
    transform: translateY(-500px);
    filter: brightness(2) hue-rotate(0deg);
  }
  50% {
    filter: brightness(2) hue-rotate(0deg);
  }
  60% {
    filter: brightness(2.5) hue-rotate(10deg);
  }
  65% {
    filter: brightness(1.2) hue-rotate(-5deg);
  }
  80% {
    filter: brightness(5) hue-rotate(0deg);
  }
  100% {
    transform: translateY(-2548px);
    filter: brightness(2) hue-rotate(0deg);
  }
}
._particleLayer1_kz2ni_54 {
  animation: _embers_kz2ni_3 30s linear -5s infinite;
}
@keyframes _embers_kz2ni_3 {
  0% {
    transform: translateY(-100px);
    filter: brightness(2) hue-rotate(0deg);
  }
  50% {
    filter: brightness(2) hue-rotate(0deg);
  }
  60% {
    filter: brightness(2.5) hue-rotate(10deg);
  }
  65% {
    filter: brightness(1.2) hue-rotate(-5deg);
  }
  80% {
    filter: brightness(5) hue-rotate(0deg);
  }
  100% {
    transform: translateY(-2148px);
    filter: brightness(2) hue-rotate(0deg);
  }
}
.yonebox > h1 {
  font-family: "SohneSchmal";
  font-size: 18.75rem;
  top: 10rem;
  color: white;
  letter-spacing: 5px;
  text-transform: uppercase;
  font-weight: 700;
  line-height: 1;
  position: relative;
}
.ytwo {
  width: 100%;
  padding: 15.625rem 2.5rem 0 2.5rem;
  box-sizing: border-box;
  margin-left: auto;
  margin-right: auto;
}
.ytwobox {
  width: 71.09375%;
  margin: 0 auto;
  justify-content: flex-start;
  align-items: flex-start;
  flex-direction: row;
  gap: 6.25rem;
}
.ytwobimg {
  justify-content: center;
  align-items: center;
  position: relative;
  z-index: 0;
}
.ytwobimg > img {
  width: 13.875rem;
  border-radius: 0.625rem;
  height: 100%;
}
.ytwobright {
  width: 73.89835%;
  flex-direction: column;
  align-items: flex-start;
}
.ytwobrtop {
  align-items: flex-start;
  gap: 2rem;
  flex-direction: column;
}
.ytwobrtop > h2 {
  color: white;
  font-size: 5.625rem;
  line-height: 90%;
  text-transform: uppercase;
  font-weight: 700;
  font-family: "SohneSchmal";
}
.ytwobrtop > p {
  line-height: 140%;
  color: white;
  text-align: left;

  font-weight: 400;
  font-size: 1rem;
}
.ytwobrtop > a {
  background-color: rgb(252 199 97);
  outline-width: 0px;
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 0.3s;
  box-shadow: inset calc(17 * 10px) 0 calc(17 * 5px) calc(17 * -5px) #ea5922;
  text-shadow: 0 1px 3px rgba(0, 0, 0, 0.5);
  padding-left: 1.5rem;
  padding-right: 1.5rem;
  display: flex;
  height: 3.9375rem;
  width: -moz-fit-content;
  width: fit-content;
  align-items: center;
  border-radius: 5px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 600;
  text-transform: uppercase;
  color: rgb(255 255 255);
  font-size: 1.125rem;
  line-height: 1.75rem;
}
.ytwobrtop > a:hover {
  scale: 1.05;
  box-shadow: inset 0 14 calc(14 * 2 / 3) calc(14 * -2 / 3) #ea5922;
  animation: 5s ease-out 0.3s infinite alternate _flicker_1cnj0_1;
}
.ytwobrbot {
  gap: 1rem;
  flex-direction: column;
  margin-top: 4rem;
}
.ytwobrbytxt {
  text-align: left;
  color: #ffffff80;

  font-size: 1rem;
  line-height: 1.5rem;
  font-weight: 400;
}
.ytwobrimgs {
  gap: 3rem;
  justify-content: flex-start;
  align-items: center;
}
.ytwobrimgs > img:nth-child(1) {
  width: 9.375rem;
}
.ytwobrimgs > img:nth-child(2) {
  width: 8.75rem;
}
.ythree {
  width: 100%;
  padding: 15.625rem 2.5rem 0 2.5rem;
  box-sizing: border-box;
  margin-left: auto;
  margin-right: auto;
}
.ythreebox {
  width: 71.09375%;
  margin: 0 auto;
  gap: 2rem;
  flex-direction: column;
}
.ythreebox > h2 {
  font-size: 90px;
  font-family: "SohneSchmal";
  font-weight: 700;
  text-align: center;
  text-transform: uppercase;
  line-height: 90%;
  color: white;
}
.ythreebtxt {
  font-size: 1.125rem;
  line-height: 1.75rem;
  text-align: center;
  color: white;
  font-family: Oxanium, ui-sans-serif, system-ui, -apple-system,
    BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, Noto Sans,
    sans-serif, "Apple Color Emoji", "Segoe UI Emoji", Segoe UI Symbol,
    "Noto Color Emoji";
}
.ythreeblist {
  width: 100%;
  gap: 1.25rem;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  display: grid;
}
.ythreeblibox {
  padding: 1.5rem;
  border: 1px solid #ffffff26;
  border-radius: 0.5rem;
  box-sizing: border-box;
  gap: 1.25rem;
  justify-content: flex-start;
  align-items: flex-start;
}
.ythreebliboxleft {
  width: 5rem;
  height: 5rem;
  border: 1px solid #ffffff40;
  border-radius: 0.25rem;
  box-shadow: 0 0 #0000, 0 0 #0000, 0px 10px 30px-0px rgba(0, 0, 0, 0.8);
  box-sizing: border-box;
}
.ythreebliboxleft > img {
  object-fit: cover;
  width: 100%;
  height: 100%;
}
.ythreebliboxright {
  gap: 0.25rem;
  flex-direction: column;
}
.ythreeblbry {
  line-height: 100%;
  font-weight: 500;
  font-size: 1.25rem;
  color: white;

  line-height: 1.25rem;
}
.ythreeblbrt {
  color: #ffffff80;

  font-size: 1rem;
  line-height: 1rem;
}
.yfour {
  width: 100%;
  padding-top: 15.625rem;
  position: relative;
}
.yfimgs {
  width: 100%;
  height: 12.3125rem;
  gap: 1.25rem;
  align-items: center;
  justify-content: center;
  gap: 1.25rem;
  position: absolute;
  left: 0;
  z-index: -10;
  overflow: hidden;
}
.yfimgbg {
  background-color: #070808cc;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  position: absolute;
}
.yfimgs > img {
  width: 16rem;
}
.yfourbox {
  width: 71.09375%;
  margin: 0 auto;
  padding-top: 12.875rem;
}
.yfourtxtcon {
  width: 100%;
  margin-top: 5rem;
  position: relative;
}
.yfourtoptit {
  gap: 2rem;
  flex-direction: column;
}
.yfourtoptit > h2 {
  font-family: "SohneSchmal";
  font-size: 90px;
  line-height: 90%;
  text-transform: uppercase;
  font-weight: 700;
  text-align: center;
  color: white;
}
.yfourtoptit > div {
  font-size: 1.125rem;
  line-height: 1.75rem;
  color: white;
  text-align: center;
}
.yfourbotbox {
  width: 82.40997%;
  margin: 3rem auto 0;
  justify-content: space-between;
  flex-direction: row;
  gap: 70px;
  align-items: center;
}
.yfourbbleft {
  width: 31.25rem;
  gap: 1.25rem;
  flex-direction: column;
}
.yfourbbleftbox {
  width: 100%;
  background-image: linear-gradient(
    105deg,
    rgba(255, 255, 255, 0.04) 37.52%,
    rgba(255, 255, 255, 0) 86.98%
  );
  padding: 1.5rem;
  border: 1px solid #ffffff26;
  border-radius: 0.5rem;
  gap: 1.25rem;
  align-items: center;
  min-height: 90px;
  box-sizing: border-box;
}
.yfourbbleftbox > img {
  width: 1.5rem;
  height: 1.5rem;
}
.yfourbbleftbox > div {
  width: 90%;
  font-size: 0.9375rem;
  line-height: 1.3125rem;
  color: white;
  font-weight: 400;
}
.yfourbbcenter {
  width: 3.125rem;
}
.yfourbbcenter > img {
  width: 100%;
}
.yfive {
  width: 100%;
  padding-top: 15.625rem;
}
.yfivebox {
  width: 71.09375%;
  margin: 0 auto;
}
.yfivebtxt {
  flex-direction: column;
  gap: 1.5rem;
}
.yfivebtxty {
  font-size: 1.125rem;
  line-height: 1.75rem;
  color: #ffffffbf;
  text-align: center;
}
.yfivebtxty > span {
  color: transparent;
  -webkit-background-clip: text;
  background-clip: text;
  background-image: linear-gradient(215deg, #fcc761 22.29%, #ea5922 90.19%);
}
.yfivebtxt > h2 {
  font-family: "SohneSchmal";
  font-size: 90px;
  line-height: 90%;
  text-transform: uppercase;
  font-weight: 700;
  text-align: center;
  color: white;
}
.yfivebtxtt {
  font-family: "SohneSchmal";
  font-size: 3rem;
  line-height: 1;
  text-transform: uppercase;
  font-weight: 700;
  text-align: center;
  color: white;
}
.yfivebtxt .yfivebtxtse {
  font-family: Oxanium, ui-sans-serif, system-ui, -apple-system,
    BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans",
    sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol",
    "Noto Color Emoji";
  font-weight: 400;
  text-align: center;
  color: transparent;
  -webkit-background-clip: text;
  background-clip: text;
  background-image: linear-gradient(215deg, #fcc761 22.29%, #ea5922 90.19%);
}
.yfivebtxtthr {
  font-family: Oxanium, ui-sans-serif, system-ui, -apple-system,
    BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans",
    sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol",
    "Noto Color Emoji";
  font-weight: 400;
  font-size: 1.5rem;
  line-height: 2rem;
  color: #ffffffbf;
  text-align: center;
}
.yfivebbot {
  margin-top: 5rem;
  justify-content: center;
}
.yfivebbotleft {
  width: 40.5rem;
  padding-right: 5rem;
}
.yfivebbotleft > img {
  width: 100%;
  object-fit: cover;
}
.yfivebbotright {
  width: 45.5rem;
  border-left: 1px solid #ffffff26;
  padding-left: 5rem;
  box-sizing: border-box;
}
.yfivebbrighty {
  gap: 1.25rem;
  flex-direction: column;
}
.yfivebbrtxty {
  font-family: "SohneSchmal";
  line-height: 90%;
  text-transform: uppercase;
  font-weight: 700;
  font-size: 3rem;
  color: white;
}
.yfivebbrtxtr {
  color: #ffffffbf;
  line-height: 140%;
  font-size: 1rem;
  line-height: 1.5rem;
}
.yfivebbrightt {
  width: 100%;
  margin-top: 5rem;
  padding: 1.5rem;
  gap: 1.25rem;
  flex-direction: column;
  background-image: linear-gradient(
    105deg,
    rgba(255, 255, 255, 0.04) 37.52%,
    rgba(255, 255, 255, 0) 86.98%
  );
  border: 1px solid #ffffff26;
  border-radius: 0.5rem;
  box-sizing: border-box;
}
.yfivebbrightty {
  color: #ffffffbf;
  line-height: 140%;
  font-size: 1.125rem;
  font-weight: 400;
}
.yfivebbrighttt {
  width: 100%;
  gap: 0.625rem;
  justify-content: flex-start;
  align-items: center;
}
.yfivebbrighttt > a {
  width: 48%;
  transition-property: color, background-color, border-color,
    text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter,
    backdrop-filter, -webkit-backdrop-filter;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 0.15s;
  padding-left: 1.5rem;
  padding-right: 1.5rem;
  background-color: #ffffff0d;
  border: 1px solid #ffffff26;
  gap: 0.9375rem;
  justify-content: center;
  align-items: center;
  height: 3.375rem;
  display: flex;
  cursor: pointer;
  box-sizing: border-box;
}
.yfivebbrighttt > a:hover {
  background-color: #ffffff1a;
}
.yfivebbrighttt > a > svg {
  width: 1.875rem;
  height: 1.875rem;
  color: white;
}
.yfivebbrighttt > a > span {
  color: #ffffffbf;
  font-size: 1rem;
  line-height: 1.5rem;
}
.ysix {
  width: 100%;
  padding-top: 15.625rem;
}
.ysixbox {
  width: 71.09375%;
  margin: 0 auto;
}
.ysixbox {
  gap: 2rem;
  flex-direction: column;
}
.ysixbox > h2 {
  font-family: "SohneSchmal";
  font-size: 90px;
  line-height: 90%;
  text-transform: uppercase;
  font-weight: 700;
  text-align: center;
  color: white;
}
.ysixboxlist {
  width: 52.6315789%;
  flex-direction: column;
  gap: 1.25rem;
  margin: 0 auto;
}
.ysixblbox {
  width: 100%;
  padding: 1.5rem;
  border: 1px solid #ffffff26;
  gap: 1.25rem;
  justify-content: flex-start;
  align-items: flex-start;
  box-sizing: border-box;
  background-image: linear-gradient(
    105deg,
    rgba(255, 255, 255, 0.04) 37.52%,
    rgba(255, 255, 255, 0) 86.98%
  );
  border-radius: 0.5rem;
}
.ysixblboxtxt {
  gap: 0.75rem;
  align-items: flex-start;
}
.ysixblbtleft {
  width: 0.375rem;
  height: 0.375rem;
  background: rgb(250 159 23);
  position: relative;
  top: 0.5rem;
}
.ysixblbtright {
  width: 97.25%;
}
.ysixblbtry {
  font-family: Oxanium, ui-sans-serif, system-ui, -apple-system,
    BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans",
    sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol",
    "Noto Color Emoji";
  font-size: 1.25rem;
  color: white;
  line-height: 140%;
  font-weight: 500;
}
.ysixblbtrt {
  font-family: Oxanium, ui-sans-serif, system-ui, -apple-system,
    BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans",
    sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol",
    "Noto Color Emoji";
  font-size: 1rem;
  line-height: 1.5rem;
  color: #ffffffbf;
  font-weight: 400;
  gap: 1rem;
  flex-direction: column;
}
.yqi {
  width: 100%;
  padding: 15.625rem 0 15rem;
}
.yqibox {
  width: 71.09375%;
  margin: 0 auto;
}
.yqibox > h2 {
  font-family: "SohneSchmal";
  font-size: 90px;
  line-height: 90%;
  text-transform: uppercase;
  font-weight: 700;
  text-align: center;
  color: white;
}
.yqibox > h2 > span {
  color: transparent;
  -webkit-background-clip: text;
  background-clip: text;
  background-image: linear-gradient(244deg, #fcc761 4.6%, #ea5922 72.12%);
}
.yqilist {
  display: grid;
  width: 100%;
  gap: 1.25rem;
  grid-template-columns: repeat(3, minmax(0, 1fr));
}
.yqilistbox {
  padding: 1.5rem;
  border: 1px solid #ffffff26;
  gap: 1.25rem;
  justify-content: flex-start;
  align-items: flex-start;
  border-radius: 0.5rem;
  background-image: linear-gradient(
    105deg,
    rgba(255, 255, 255, 0.04) 37.52%,
    rgba(255, 255, 255, 0) 86.98%
  );
}
.yqilistbleft {
  width: 5rem;
  height: 5rem;
  border: 1px solid #ffffff40;
  border-radius: 0.25rem;
  box-sizing: border-box;
}
.yqilistbleft > img {
  width: 100%;
  border-radius: 0.25rem;
}
.yqilistbright {
  gap: 1.25rem;
  flex-direction: column;
}
.yqilistbrightyy {
  font-size: 1.25rem;
  font-weight: 500;
  line-height: 100%;
  color: white;
}
.yqilistbrightyt {
  font-size: 1rem;
  line-height: 1rem;
  color: #ffffffbf;
  font-weight: 400;
}
.yqilistbrighty {
  gap: 0.625rem;
  justify-content: flex-start;
  align-items: center;
}
.yqilistbrighty > a {
  width: 1.125rem;
}
.yqilistbrighty > a > svg {
  width: 100%;
  color: white;
}
.yfoot {
  width: 100%;
  padding: 8.4375rem 3rem 2rem;
  box-sizing: border-box;
}
.yfootimgs {
  width: 100%;
  align-items: center;
}
.yfootimgs > a:nth-child(1) {
  display: block;
  height: 5rem;
}
.yfootimgs > a:nth-child(2) {
  display: block;
  height: 1.25rem;
  margin-left: 7rem;
}
.yfootimgs > a:nth-child(3) {
  display: block;
  height: 3.75rem;
}
.yfootimgs > a:nth-child(1) > img {
  height: 100%;
}
.yfootimgs > a:nth-child(2) > img {
  height: 100%;
}
.yfootimgs > a:nth-child(3) > img {
  height: 100%;
}
.yfootimgsy {
  width: 100%;
  gap: 1rem;
  text-align: center;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.yfootimgsy > img {
  width: 2.1875rem;
}
.yfootimgsy > div {
  color: #ffffffbf;
  font-size: 1rem;
  line-height: 1.5rem;
}
</style>
