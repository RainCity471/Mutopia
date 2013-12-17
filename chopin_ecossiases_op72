\version "2.17.97"
% http://erato.uvt.nl/files/imglnks/usimg/b/bc/IMSLP00628-Chopin_-_3_Ecossiases__Op_72.pdf
mBreak = { \break }
red = { \once \override NoteHead #'color = #red }
mfbrilliante = _\markup { {\dynamic mf} {\italic brilliante} }

\new PianoStaff <<
	\new Staff {
		\clef "treble"
		\time 2/4
		\key d \major
		\tempo "Vivace" 4 = 108
			\relative c' {
				\partial 8 fis8-1( |
				a16-2)\mfbrilliante[ % ----¬
				           r32 b'-5(  a16)     r32 g,-1(]   a16)[   r32 b'-5(  a16)   r32 fis,-1]( |
				a16)[      r32 b'(    a16)     r32 fis,](   a16)[   r32 e''-5( d16)   r32 cis-3](  |
				b16)[\cresc r32 ais-4( b16)     r32 dis,-2]( e16)[   r32 fis-2( g16)   r32 \red a-2](    | % shouldn't the {a} be {ais}? I think this is a printing error
				\mBreak
				b16)[      r32 e,-1(\<  e16-2-.) r32 fis-3](  e16-.)[ r32 fis-2( g16-.) r32 gis-4](\!  |
				\red \acciaccatura a,8 % ----¬
				a'16-.)[\f   r32 \ottava #1 % ----¬
							   b'(  a16)     r32 g,(]   a16)[   r32 b'(  a16)   r32 fis,]( |
				a16)[      r32 b'(    a16)     r32 fis,](   a16)[   r32 e''-5( d16)   r32 cis-3](  |
%				TBC...
			}
	}
% ============================================================================
	\new Staff {
		\clef "bass"
		\time 2/4
		\key d \major
			\relative c {
				\partial 8 r8 |
				<d fis d'>8-. a' <cis, g' e'>-. a'            |
				<d, fis d'>-. a' fis, <fis' a d> |
				g,-. <g' b^4 dis-2>-.[ <g b^3 e-1>-.] r8 |
				<g b e> <gis-5 b-3 d e>-. <a-4 cis e> r8 |
			}
	}
>>
