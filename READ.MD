	<!-- Banner image at the bottom, full width, responsive -->
	<div class="fixed bottom-0 left-0 w-screen z-50">
		<img
			src="/assets/images/lo.jpg"
			alt="Login Image"
			class="w-full h-32 sm:h-48 md:h-64 object-cover object-center rounded-none border-0 shadow-none select-none pointer-events-none"
		/>
	</div>
</div>

import pyotp
totp = pyotp.TOTP("XX")
print("קוד כניסה:", totp.now())

